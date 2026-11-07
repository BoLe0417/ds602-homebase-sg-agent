# Platform settings (SMU AI Studio)

Kept identical for V1 and V2 so that differences come only from the agent design.

- **Model:** gpt-5.6-sol (same model settings for both versions)
- **Tools:** Web search ✅, File search ✅ (needed to read the knowledge file)
- **Not used:** code runner, artifacts, academic search, image generation
- **Knowledge file:** [`../knowledge/SG_Rental_Knowledge.txt`](../knowledge/SG_Rental_Knowledge.txt)
- **Skills:** none in V1; `compare-rental-options` and `scam-and-contract-check` in V2
