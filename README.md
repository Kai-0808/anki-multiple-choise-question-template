### Enhanced Multiple Choice Question Template for Anki with Group Questions Support

This repository contains enhanced template for front and back cards, designed specifically for styling multiple choice questions in Anki with support for **group of questions** (up to 5 questions per card).

**Based on the work by [muctebanesiri](https://github.com/muctebanesiri/anki-multiple-choise-question-template)**

![example](https://github.com/user-attachments/assets/ad63d36e-43f2-4e91-953f-e29cda14d86f)

### ✨ New Features

- **Group of Questions Support**: Create cards with up to 5 questions instead of just one
- **Enhanced Layout & Styling**: Clearer question blocks with better visual separation and organization
- **Note ID for Card Management**: Added optional Note ID field for clear card identification and organization
- **Enhanced Answer Feedback**: Improved visual feedback system with clear notation symbols:
  - **✅ Green Checkmark**: Correct answer that you selected
  - **⚠️ Orange Warning**: Correct answer that you missed (didn't select)  
  - **❌ Red X**: Incorrect answer that you selected
  - **Green Background**: All correct answers are highlighted for easy identification
- **Ruby Text Support** (not contained in `MCQ_Demo.apkg`): Added support for ruby text (especially for Japanese furigana) to allow readability assistance

### 🗑️ Removed Features

- **LTR Layout Only**: Focused on left-to-right language layout for simpler, more maintainable code
- **Removed Auto-Submit**: Eliminated automatic submission feature that may have caused confusion for multiple questions case

### Field Names for this Template

```
Main_text (optional)
Note_ID (optional)
Question_1
Question_2 (optional)
Question_3 (optional) 
Question_4 (optional)
Question_5 (optional)
option_1_1 (A) through option_1_8 (H) for Question 1
option_2_1 (A) through option_2_8 (H) for Question 2
... (similarly for Questions 3-5)
Ans_1, Ans_2, Ans_3, Ans_4, Ans_5
Explanation (optional)
```

### Codes

1. **Front Template** - Refer to `front.html` under `Code/`
2. **Back Template** - Refer to `back.html` under `Code/`
3. **Styling** - Refer to `style.css` under `Code/`

### Answer Format Examples
- Single answer: `A`
- Multiple answers: `BC` or `ADE` 
- Number format also supported: `1` or `23` (converted to letters)

### Feature Summary (Included the Original Features)
- ✅ Up to 5 questions per card
- ✅ Up to 8 options (A-H) per question  
- ✅ Multiple correct answers per question
- ✅ Option shuffling with persistence
- ✅ Zoom controls for better readability
- ✅ Text highlighting capability
- ✅ Dark mode support

### 🙏 Credits & Development

This enhanced version builds upon the foundation created by [muctebanesiri](https://github.com/muctebanesiri), whose original multiple choice template provided the starting point for these improvements. The original code foundation was initially provided/modified by u/12yardsfootball and further enhanced by muctebanesiri with RTL support and other features.

**Development transparency**: Almost all the enhancements and coding work for this multi-question version were accomplished by **Claude 3.7 Sonnet**. I currently don't have much knowledge in this domain, but wanted to create a more comprehensive multiple choice template for my Anki studies, and the AI helped transform the original single-question template into this enhanced multi-question version with improved visual feedback, better organization, and additional features.

### Backward Compatibility

If you are using the original template, you may need to first rename existing fields and add new fields to your notes manually, then replace the original HTML and CSS code with the this version. While this approach should work in theory, I have not tested it extensively. **Make sure to back up your original template and notes before making any changes**.

**Migration steps (untested):**
1. Back up your current template and notes
2. Rename existing fields to match the new field structure
3. Add the additional fields for multi-question support
4. Replace the template code with the enhanced versions

If you successfully migrate from the original template, please consider sharing your experience to help improve these instructions.

---

**Original Repository**: [muctebanesiri/anki-multiple-choise-question-template](https://github.com/muctebanesiri/anki-multiple-choise-question-template)
