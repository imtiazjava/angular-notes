# angular-notes

---------------------------------
PROJECT NAME : ONLINE SHOPPING
  components ;
       onlineshopping
       appliances
         -lighting
         -furniture
       electronics
         - mobile
         - laptop
       fashion
          -men
          -women
          -kids
   ```
var configure:Routes=[
{
 path:'',component:OnlineshoppingComponent
},

{
 path:'appliances',component:Appliancecomponent,
        children:[
             {path:'lighting',component:LightingComponent},
             {path:'furniture',component:'FurnitureComponent'}

        ]
},
{
  path:'electronics',component:ElectronicsComponent,
         children:[
               {path:'mobile',component:MobileComponent},
               {path:'laptop',component:LaptopComponent}
         ]
}
...
]
```

# add the bootstrap 
--------------------------
<!doctype html>
<html lang="en">
<head>
  <meta charset="utf-8">
  <title>Emsapp</title>
  <base href="/">
  <meta name="viewport" content="width=device-width, initial-scale=1">
  <link rel="icon" type="image/x-icon" href="favicon.ico">

     <link rel="stylesheet" href="https://cdn.jsdelivr.net/npm/bootstrap@4.6.2/dist/css/bootstrap.min.css" integrity="sha384-xOolHFLEh07PJGoPkLv1IbcEPTNtaed2xpHsD9ESMhqIYd0nLMwNLD69Npy4HI+N" crossorigin="anonymous">


 </head>
<body>
  <app-root></app-root>

  <script src="https://cdn.jsdelivr.net/npm/jquery@3.5.1/dist/jquery.slim.min.js" integrity="sha384-DfXdz2htPH0lsSSs5nCTpuj/zy4C+OGpamoFVy38MVBnE+IbbVYUew+OrCXaRkfj" crossorigin="anonymous"></script>
  <script src="https://cdn.jsdelivr.net/npm/popper.js@1.16.1/dist/umd/popper.min.js" integrity="sha384-9/reFTGAW83EW2RDu2S0VKaIzap3H66lZH81PoYlFhbGU+6BZp6G7niu735Sk7lN" crossorigin="anonymous"></script>
  <script src="https://cdn.jsdelivr.net/npm/bootstrap@4.6.2/dist/js/bootstrap.min.js" integrity="sha384-+sLIOodYLS7CIrQpBjl+C7nPvqq+FbNUBDunl/OZv93DB7Ln/533i8e/mZXLi/P+" crossorigin="anonymous"></script>

</body>
</html>

