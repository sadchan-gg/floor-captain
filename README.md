# Floor Captain: in-store mobility prototype

A clickable concept prototype from our Wipro consulting live project, *Off-price retail: the future of in-store mobility* (point of view for Ross and TJX).

**Open the prototype:** https://sadchan-gg.github.io/floor-captain/

It follows one associate through a morning in a store, one step per prioritised use case:

1. **Morning truck: best sellers first** (UC2 Truck-to-rack guide)
2. **Start of shift: a ranked task list** (UC3 AI task list and store walks)
3. **A shopper needs help** (UC4 Connected associate)
4. **Lunch rush: a pop-up till** (UC1 Pop-up till with rush alerts)
5. **Manager view: the store at a glance** (Floor Captain agent and guardrails)

The **Floor Captain agent · live** panel on the right shows what the agent is doing at each step:
- It runs a Sense → Decide → Act → Learn cycle.
- It reacts to every tap on the phone.
- It labels each action with who decides: the agent on its own, by asking the associate, by asking the manager, or never.

On the lunch-rush step, two **what-if sliders** (shoppers per hour and tills open) make the agent re-plan live.

**Test a guardrail** buttons show the actions it always refuses: changing shifts, ranking people and using cameras.

The panel runs in the browser with no AI calls. Forecasts use an M/M/c queue model and rankings use simple scores, the same logic as our Python agent.

Use **Next step** or the arrow keys to move between steps. Each step can also be opened directly, from `#step1` to `#step5` (for example https://sadchan-gg.github.io/floor-captain/#step3).

This is a concept prototype for a student consulting project. It is not a Ross or TJX product, and all names, prices and store numbers are illustrative. The whole prototype is one HTML file. It loads its fonts from Google Fonts and collects no data.
