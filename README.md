Craps Bet Simulation in Python

This project models several bets in the casino game of Craps, running large-scale tests to explore outcomes and probabilities. Each bet is tested 50,000 times at a flat $25 wager to measure:
	•	Win percentage
	•	Loss percentage
	•	Push frequency
	•	Total net win/loss
	•	Average return per round
	•	House edge (calculated from simulated results)

Current Features

For this first version, the model covers:
	•	Pass Line
	•	Don’t Pass
	•	Field
	•	Any Seven
	•	Any Craps

Each bet follows its rules as played on a real craps table, including come-out rolls, point establishment, and one-roll wagers.

Purpose

This project combines my background in casino operations with programming and analytics. By simulating tens of thousands of rounds, it provides a way to see how different bet types behave over time and how the house edge emerges in practice.

It also marks my first step into larger-scale simulations, moving beyond small probability tests into structured modeling through code.

⸻

Next Steps
	•	Expanding the model to include all craps bet types
	•	Allowing variable wager amounts
	•	Introducing enums to organize and manage bet types, making the code cleaner and easier to scale
