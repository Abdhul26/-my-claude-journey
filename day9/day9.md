📌 What I learned building a full nutrition app with Claude — in two prompts
Most people prompt AI like they're texting a friend: "build me a nutrition app." Then they're disappointed with generic output.
I tested the opposite approach: treat the prompt like a spec document, not a request.
❌ Weak prompt:
"Build me a nutrition tracking app with charts and recommendations."
✅ Improved prompt (what I actually used):
"Build a complete single-file HTML application called NutriScope.
Requirements:
Profile Inputs: Age, gender, Height, Weight, Activity Level, Dietary Preference...
Food Logging: Add Food, Quantity, Unit, Editable Table, Remove Entry...
Food Database: Include 20 common foods only: Rice, Roti, Dal...
Track: Calories, Protein, Carbs, Fat, Fiber, Iron, Calcium...
Calculations: Energy, Macro Targets, Micronutrient Targets, Percentage Completion...
[+ Dashboard, Recommendations, Design specs]"
The difference wasn't tone — it was structure. Naming each subsystem (Inputs → Logic → Output → Design) as its own labeled block gave the model clear boundaries, so it built a coherent system instead of a generic one.
The bigger lesson came at step two. For the enhancement pass, I didn't say "make it better." I gave a flat list: CSV Upload, 40 more foods, Additional micronutrients, 2-day meal planner, Risk Analysis, Educational Disclaimer... Nine features, one prompt, zero ambiguity — and every existing feature stayed intact while new ones slotted in.
Takeaway: A good prompt isn't longer, it's itemized. Break your ask into labeled requirement blocks the way you'd write a PRD, and the output starts looking like one too.
What's surprised you most about how much prompt structure — not just wording — changes the output?
#AbtalksClaudeChallenge #PromptEngineering #AI #Claude
🏷️ Anil Bajpai | ABTalksonAI | Anthropic
