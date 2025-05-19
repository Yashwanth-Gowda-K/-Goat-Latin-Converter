# -Goat-Latin-Converter

🚀 Problem Statement
Convert a given English sentence to Goat Latin using these rules:
1. Words starting with vowels: Append `"ma"`
   - Example: `"apple"` → `"applema"`
2. Words starting with consonants: Move first letter to end + `"ma"`
   - Example: `"goat"` → `"oatgma"`
3. Append increasing `'a'`s based on word position
   - First word: `+a`, second: `+aa`, etc.

**Example:**
```python
Input: "I speak Goat Latin"
Output: "Imaa peaksmaaa oatGmaaaa atinLmaaaaa"
🛠 Solution Features
O(n) time complexity - Efficient processing of each word

Case-insensitive vowel checks using set for O(1) lookups

Space-efficient - Uses list comprehensions and generator expressions

Error handling for empty inputs
