# Curated samples (good vs bad)

Goal: build a small, high-quality reference set of vehicle exhaust smoke examples for (a) training and (b) user guidance.

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
