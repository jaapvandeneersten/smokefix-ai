# Curated samples (good vs bad)
Goal: build a small, high-quality internal reference set (ground truth) for validation/testing and sanity checking. This is primarily internal test data (not user-facing guidance).
## Sources
- Roboflow Universe: Vehicle smoke pollution dataset (images + annotations) https://universe.roboflow.com/ta-gomsn/vehicle-smoke-pollution
- Roboflow Universe: Vehicle smoke pollution dataset v18 (downloads in many formats) https://universe.roboflow.com/ta-gomsn/vehicle-smoke-pollution/dataset/18
- Roboflow Universe: Car with smoke dataset https://universe.roboflow.com/cars-v04ul/car-with-smoke/dataset/2
- PoVSSeg / DB-Net-Vehiclesmoke (repository reference) https://github.com/Chen-Junyao/DB-Net-Vehiclesmoke/
- Pexels: car exhaust smoke videos https://www.pexels.com/search/videos/car%20exhaust%20smoke/
- Pixabay: car smoke videos https://pixabay.com/videos/search/car%20smoke/

⚠️ Licensing: Roboflow datasets are typically CC BY 4.0; stock video sites have their own license/attribution rules. Always keep attribution info with the files and check before releasing any dataset.

## Good example checklist
- Exhaust and vehicle are visible (rear/side angle works best)
- Smoke clearly visible and distinguishable from background
- Good lighting / high contrast
- Minimal motion blur; camera fairly steady
- Shows when smoke occurs (idle vs acceleration) when possible

## Bad example checklist (reject)
- Exhaust not visible / not a vehicle
- Strong glare at night
- Heavy motion blur / shaky camera
- Wrong subject (bonfire, factory smoke, cigarette)
- Dust clouds labeled as smoke

## Next step
- Pick 20 good and 20 bad links from the sources above.
- Keep them listed here first (no need to commit large media files yet).

## Curated example links (seed)
### Good examples
- Clear rear view, exhaust visible, thick black smoke: https://www.example.com/good/black-smoke-rear-view
- Rear view, exhaust + white smoke visible: https://www.example.com/good/white-smoke
- Close exhaust shot with visible smoke plume: https://www.example.com/good/close-exhaust

### Bad examples
- Dust cloud behind vehicle (reject): https://www.example.com/bad/dust-cloud
- Night glare/headlights flaring (reject): https://www.example.com/bad/night-glare
- Wrong subject (bonfire smoke): https://www.example.com/bad/bonfire

## Curated example links (real)
### Good examples
- https://images.pexels.com/photos/5233283/pexels-photo-5233283.jpeg?auto=compress&cs=tinysrgb&dpr=1&w=500
- https://images.pexels.com/photos/5233282/pexels-photo-5233282.jpeg?auto=compress&cs=tinysrgb&dpr=1&w=500
- https://images.pexels.com/photos/5233284/pexels-photo-5233284.jpeg?auto=compress&cs=tinysrgb&dpr=1&w=500
- https://images.pexels.com/photos/10658552/pexels-photo-10658552.jpeg?auto=compress&cs=tinysrgb&dpr=1&w=500
- https://www.pexels.com/search/car%20exhaust%20smoke/

### Bad examples
- https://unsplash.com/photos/rally-car-kicks-up-a-huge-cloud-of-dust-ZoH1Z1muGeo
- https://images.pexels.com/photos/8523442/pexels-photo-8523442.jpeg?auto=compress&cs=tinysrgb&dpr=1&w=500
- https://images.pexels.com/photos/17793382/pexels-photo-17793382/free-photo-of-fast-rotating-car-wheel.jpeg?auto=compress&cs=tinysrgb&dpr=1&w=500
- https://images.pexels.com/photos/6740947/pexels-photo-6740947.jpeg?auto=compress&cs=tinysrgb&dpr=1&w=500
- https://pixabay.com/images/search/bonfire/
