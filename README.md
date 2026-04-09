# Poetry Assistant (JavaScript)

## Overview
The Poetry Assistant is a simple JavaScript-based application designed to suggest rhyming words for a given input word. It uses a predefined word list and compares patterns in words to generate rhymes.

This project demonstrates string manipulation, array processing, and basic algorithm design.

---

## Features

- ✍️ Input a word and get rhyming suggestions  
- 🔤 Uses pattern matching (last two letters)  
- 📚 Large word dataset for rhyme generation  
- 🔁 Alternative implementation using stack (reverse order output)  
- ⚡ Fast lookup using simple iteration  

---

## Technologies Used

- JavaScript (ES6)
- HTML (basic structure)

---

## How It Works

The program follows a simple logic:

1. Extract the last two letters of the input word  
2. Loop through a word list  
3. Compare the last two letters of each word  
4. If they match → it's considered a rhyme  
5. Return all matching words  

Example logic:

```javascript
function getLastTwoLetters(word) {
    return word.substring(word.length - 2);
}

## File Structure

index.html → Loads the scripts
Poetry Assistant.js → Main rhyme logic
wordlist.js → Word dataset
words.txt → Extended dictionary dataset

## Example Output

Input: cat
Output: bat, hat, mat, rat, flat, ...

## Key Learnings
1.String manipulation techniques
2.Array traversal and filtering
3.Algorithm design for pattern matching
4.Using stacks for reversing output order
5.Structuring JavaScript programs

## Limitations
1.Rhyming is based only on last two letters (not phonetics)
2.Some results may not be true rhymes
3.No UI (console-based output only)

## Future Improvements
1.Use phonetic matching (better rhyme accuracy)
2.Add a web interface (input box + results display)
3.Improve performance using hash maps
4.Support sentence or poem suggestions
5.Integrate NLP techniques