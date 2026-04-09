# Poetry Assistant (JavaScript)

## Overview
The Poetry Assistant is a simple JavaScript-based application designed to suggest rhyming words for a given input word. It uses a predefined word list and compares patterns in words to generate rhymes.

This project demonstrates string manipulation, array processing, and basic algorithm design.

---

## Features

- ✍️ Input a word and get rhyming suggestions  
- 🔤 Pattern matching using last two letters  
- 📚 Uses a word dataset for rhyme generation  
- 🔁 Stack-based implementation (reverse output order)  
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
4. If they match → it is considered a rhyme  
5. Return all matching words  

### Example Logic

    function getLastTwoLetters(word) {
        return word.substring(word.length - 2);
    }

---

## File Structure

    index.html            # Loads the scripts
    PoetryAssistant.js    # Main rhyme logic
    wordlist.js           # Word dataset
    words.txt             # Extended dictionary dataset

---

## Example Output

Input:
    cat

Output:
    bat, hat, mat, rat, flat, ...

---

## Key Learnings

- String manipulation techniques  
- Array traversal and filtering  
- Algorithm design for pattern matching  
- Using stacks for reversing output order  
- Structuring JavaScript programs  

---

## Limitations

- Rhyming is based only on last two letters (not phonetics)  
- Some results may not be true rhymes  
- No graphical UI (console-based output)  

---

## Future Improvements

- Implement phonetic matching for better accuracy  
- Add a web interface (input + results display)  
- Improve performance using hash maps  
- Support full sentence or poem generation  
- Integrate NLP techniques  
