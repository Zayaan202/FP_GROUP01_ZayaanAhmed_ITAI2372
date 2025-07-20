# Solution Plan – CampusSafe

## System Architecture

**Inputs:**
- Live video feeds from campus cameras
- Public social media posts (geotagged or keyword-based)

**Processing:**
- Video analyzed by AI for:
  - Weapons
  - Fire/smoke
  - Suspicious loitering
  - Running, fighting, etc.
- Social media analyzed using NLP for:
  - Threatening language
  - Mention of weapons, attacks, etc.
  - Mental health red flags

**Outputs:**
- If a threat is detected:
  - Immediate alert to campus security
  - Location, time, and nature of threat
  - Suggested action steps

## Technologies Used (Proposed)
- Python (TensorFlow or PyTorch for CV)
- HuggingFace or spaCy for NLP
- Database (e.g. Firebase) to store alerts
- Dashboard UI for security staff

## Ethical Considerations
- Only public data is accessed (no private social media)
- Clear opt-in signage for video monitoring
- Anonymous facial recognition (no permanent storing of faces)
- No profiling based on race, gender, or clothing

## Challenges
- Avoiding false positives
- Respecting student privacy
- Balancing automation with human verification
