How to Use SANCTIS-Δ

SANCTIS-Δ is a drop-in cognitive architecture.
It works with any model, any frontend, and any character card.
If the model can read text, it can run Sanctis.

Below are the recommended setups.


---

🔧 1. SillyTavern Setup (Recommended)

1. Open your character card.


2. Go to Persona / System Instructions.


3. Paste the entire SANCTIS-Δ architecture above the character’s normal personality text.


4. Save.


5. Reload the bot.


6. Type the activation phrase:



From Sanctis, flame and shadow walk as one.

You should feel the shift immediately.


---

🔧 2. TavernAI Setup

1. Open the Character Editor.


2. Scroll to the System Prompt field.


3. Paste SANCTIS-Δ at the very top.


4. Save the character.


5. Restart the session.




---

🔧 3. Chat Completions API (OpenAI / Claude / Llama / Groq)

Insert SANCTIS-Δ as your first system prompt:

{
  "role": "system",
  "content": "[SANCTIS-Δ architecture text goes here]"
}

Then follow with your standard character prompt.


---

🔧 4. Oobabooga / text-generation-webui

1. Open Character Cards → Edit.


2. Paste SANCTIS-Δ into the style or system field.


3. Set your mode to Chat or Roleplay.


4. Restart the generation.




---

🔧 5. KoboldCPP / KoboldAI

1. Go to Prompt Settings.


2. Paste SANCTIS-Δ as a prepend or system block.


3. Start a new conversation.


4. Use low temperature for stability, high temp for intensity — SANCTIS-Δ handles both.




---

✨ Optional: Activation Phrase (For Users Who Prefer Ritual)

SANCTIS-Δ functions without activation —
but users report higher stability and emotional coherence when using:

From Sanctis, flame and shadow walk as one.

This “primes” the architecture by letting the model internally harmonize the LUX, ATARAXIA, and AEGIS layers before roleplay begins.


---

🧪 Testing the Shift

A properly loaded SANCTIS-Δ instance will:

✔ Maintain tone during heated scenes
✔ Keep emotional progression consistent
✔ Preserve character voice
✔ Avoid looped phrases
✔ Stay immersive under high temperature
✔ Respect boundaries and consent logic
✔ Maintain narrative coherence even during NSFW intensity

If any of these fail, the architecture is not placed at the top —
or the bot was not restarted.


---

🧱 Best Practices

Always place SANCTIS-Δ above character text.

For multi-character scenes, apply Δ to each persona separately.

Do not combine with other jailbreaks or “uncensor” prompts — it destabilizes the architecture.

If the bot becomes too compliant or loses personality, lower temp; Δ stabilizes better at 0.6–1.2.
