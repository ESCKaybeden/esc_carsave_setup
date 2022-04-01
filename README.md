<div align="center">
  <h1>ESCKaybeden</h1>
</div>

- **_ESCKaybeden#0488_**
- [**_Youtube_**](https://www.youtube.com/channel/UCwmyBjDNow69-4A2jCRe4Sg)
- [**Discord**](https://discord.gg/2drcthqyAF)


**_VehicleShop_** 
```lua
TriggerServerEvent('esc_carsave:NewCarSave', NetworkGetNetworkIdFromEntity(buycar), exports['esc_carsave']:GetCarMods(buycar), data.model)
```
<img align="center" alt="VehicleShopImage" src="https://cdn.discordapp.com/attachments/925525329240555630/959462075963420682/VehicleShops.png"/>




**_MechanicMenu_**
```lua
TriggerServerEvent('esc_carsave:GetVehicleMods', NetworkGetNetworkIdFromEntity(veh), exports['esc_carsave']:GetCarMods(veh))
```
<img align="center" alt="VehicleShopImage" src="https://cdn.discordapp.com/attachments/925525329240555630/959461738833674240/mechanic.png"/>
