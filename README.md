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
