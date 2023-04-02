# acehack2.0
Hackathon Project
Our problem statement:
Q7. Production of reserved or unlicensed weapons such as gun, fighter jets, missiles etc. may raise huge problem in society and leads to the unsafe environment. These weapons are marked with an authentic license number. Design a model to track the production of weapons between seller and dealer using immutable and hack proof using Block Chain technology. This model should also track the counterfeit documents, which is submitted by the individuals to take the weapons with fake license. It will help lots to minimize the number of criminals.

Solution: We have got a proper solution for the given problem statement.
What we did was make a smart contract using ethereum in remix ide environment, where we generated various tokens for the approval of a licensed firearm(weapon) from dealer to seller starting from production.

We kept track of every gun producedwith the help if ID and various other factors such as Manufacturer, model, serial number etc to authenticate the production of a weapon. Then we issued license of the produced weapon which acts a authenticate document for the weapon. Then we kept track of the seller and buyer identity where a counterfiet document produced by frauds can be detected as the license number of the weapon would not match with the licensenumber that the buyer provides without actually making a license for the weapon. And furthermore the buyer and seller licensew is verified by their addresses. If a fraud document were to be detected then the transaction would lead to a failure and the token would be returned to the original place along with currency values.
