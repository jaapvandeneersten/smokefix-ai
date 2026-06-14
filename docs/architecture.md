# Architecture

## MVP
- **Flutter mobile app** captures exhaust video + photos (rear, dashboard, engine bay, engine plate)
- Sends media to backend for **Gemini multimodal analysis**
- AI returns: smoke type, likely causes, and a **visual checklist**
- User uploads after-video; AI compares before/after and estimates improvement
- Results stored (anonymized) for learning + impact metrics

## Minimum viable backend
- Firebase Auth (optional)
- Firebase Storage for media
- Firestore for case metadata + impact stats
- Cloud Functions for routing requests to Gemini and enforcing simple quotas

## Future (optional)
- Fleet dashboards (impact per vehicle type/route)
- Partnerships with garages/inspection stations
- Offline-first capture + delayed upload
