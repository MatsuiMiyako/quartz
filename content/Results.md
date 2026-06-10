## Data Table

| Drink             | LED Photo                      | Hex Code | R   | G   | B   | Brightness Score (/255) |
| ----------------- | ------------------------------ | -------- | --- | --- | --- | ----------------------- |
| Plain water       | ![[Water LED.png]]             | 580000   | 88  | 0   | 0   | 29/255                  |
| Coconut water     | ![[Coconut Water LED.png]]     | fd1c54   | 253 | 28  | 84  | 122/255                 |
| Homemade solution | ![[Homemade Solution LED.png]] | fe0130   | 254 | 1   | 48  | 101/255                 |
| Powerade          | ![[Powerade LED.png]]          | fe001f   | 254 | 0   | 31  | 95/255                  |
| Gatorade          | ![[G-Zero LED.png]]            | ff002a   | 255 | 0   | 42  | 99/255                  |
> Brightness = (R + G + B) ÷ 3
> Note: I used a color picker tool and centered it to the middle of the LED to determine my values.

---

## Observations

- I was actually surprised that water had a brightness at all until I realized that tap water isn't actually 100% pure water, and that the minerals in the water will affect it's conductivity. Pure water is actually a insulator!
- Coconut water scoring highest was unexpected since it's a natural drink, but this makes sense because coconut water is actually naturally very high in potassium (K⁺), sometimes higher than commercial sports drinks
- Gatorade, Powerade, and the homemade solution all scored surprisingly close together, suggesting that a simple salt-and-lemon homemade solution can actually replicate commercial sports drinks fairly well in terms of ion content
- The difference between plain water (29/255) and the top drink coconut water (122/255) is significant; coconut water was roughly 4x brighter, showing a clear relationship between ion concentration and conductivity
- The homemade solution (101/255) performed comparably to Powerade (95/255) and Gatorade (99/255), which suggests that expensive commercial sports drinks may not offer significantly more electrolytes than a simple kitchen recipe
- This means athletes could potentially save money making their own electrolyte drinks
- The brightness scores between Gatorade, Powerade, and the homemade solution were so close (95-101) that they fall within a possible margin of error, meaning more trials would be needed to confirm which is truly higher
- Plain water being non-zero (29/255) supports the chemistry principle that tap water contains trace dissolved minerals like calcium and magnesium from municipal water treatment
---

[[Analysis|Next: Analysis →]]
