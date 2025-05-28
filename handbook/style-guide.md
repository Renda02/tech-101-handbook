# Documentation Style Guide and Handbook

This handbook defines our documentation standards and writing conventions. All documentation must follow these guidelines to ensure consistency, clarity, and professionalism across our content.

## Base Style Guide

We follow the **Google Developer Documentation Style Guide** with specific deviations outlined below. All writing uses **American English conventions**.

## Language and Grammar

### Voice and Tense
- **Write in active voice**, not passive
- **Use present tense** and avoid "will"
- **Prefer verbs over nouns** (avoid nominalizations)

**Examples:**
- ✅ "The system processes payments"
- ❌ "Payments are processed by the system"
- ✅ "Click the button"
- ❌ "The button will be clicked"

### Sentence Structure
- **Limit sentences to 26 words maximum**
- **Cut unnecessary words** and prefer shorter constructions
- Use "can" instead of "will be able to"
- **Don't write in clipped language** - include articles like "the"
- **Put conditional clauses before instructions**

**Examples:**
- ✅ "If you need support, contact the team"
- ❌ "Contact the team if you need support"

### Language Style
- **Use positive language**, not negative
- **Avoid double negatives**
- **Don't preannounce** anything
- **Avoid corporate jargon** like "reach out" - use "contact" or "email"
- **Don't say "please"** in instructions

## Punctuation and Format

### Commas and Semicolons
- **Use Oxford/serial commas**
- **Generally avoid semicolons** - write separate sentences instead

### Quotation Marks
- **Use single quotation marks** in front matter of markdown files
- **Use double quotes** for error messages in plain text

**Examples:**
- Front matter: `title: 'Documentation guide'`
- Error messages: The user sees a "Payment failed" error

### Abbreviations and Acronyms
- **It's OK to use "e.g."** (preceded but not followed by a comma)
- **Define acronyms when first used**
- **Don't use acronyms in headings**
- **Don't introduce acronyms** if only used a couple of times

**Example:**
- ✅ "This applies to Belgian payment methods, e.g. Bancontact, Belfius"

### Numbers and Dates
- **Write all numbers as numerals**, including 1-10
- **Write dates in full** with US notation
- **For numerical date format**, prefer European standard DD-MM-YYYY

### Symbols
- **Don't use ampersands (&)** - write "and"
- **Use "via" only for "via our API"** - otherwise avoid

## Capitalization and Formatting

### Headings and Titles
- **Use sentence case** for titles and headings

### UI Elements
- **Write all UI elements in sentence case** regardless of actual interface
- This includes buttons, dropdown lists, fields, etc.

**Examples:**
- ✅ Click the **Submit** button
- ❌ Click the **SUBMIT** button

## Lists and Instructions

### List Types
- **Numbered lists** for processes where order matters
- **Bulleted lists** for non-processes where order doesn't matter
- **Format lists correctly** - ensure grammatical and conceptual parallelism

### Introductory Sentences
Use clear, direct introductions:

**For simple processes:**
- "To get the USB driver:"

**For complex processes:**
- "To configure the payment system, follow these steps:"

### List Examples
**Process list (numbered):**
1. Click **Tools** > **Android** > **SDK Manager**
2. Select **Google USB Driver**
3. Click **OK**

**Feature list (bulleted):**
Use the **Submit** button to:
- Submit the form
- Indicate completion
- Allow the next person to enter data

## Links and References

### Link Text
- **Use descriptive link text**
- **Put full stops after links** at end of sentences
- **Don't put full stops after email addresses**

### External References
Format as: **Source title** – **Specific page name** (sentence case, original language)

**Examples:**
- For more information, see Hugo – Aliases
- To import data, see Snelstart – Klantenservice

### Email Format
End with email address, no full stop:
- "For support, email the Dev Team at support@company.com"

## Word Choice

### Permissions vs. Actions
- **Use "allow" only for permissions**
- **Use "let" for enabling actions**

**Examples:**
- ✅ "The admin role allows access to sensitive data"
- ✅ "This feature lets you export reports"

### Preferred Terms
| Instead of | Use |
|------------|-----|
| reach out | contact, email |
| will be able to | can |
| in order to | to |
| utilize | use |
| prior to | before |

## Error Messages and Feedback

### Error Message Format
Write error messages in plain text between double quotes:
- ✅ The customer gets a "This device is not supported" error
- ✅ Users see "Payment processing failed" when the connection times out

### User Feedback
- **Be specific about what happened**
- **Provide clear next steps**
- **Use positive language when possible**

## Quality Checklist

Before publishing, verify:

### Content Structure
- [ ] Headings use sentence case
- [ ] Lists are parallel in structure
- [ ] Instructions are in logical order
- [ ] Conditional clauses come before instructions

### Language
- [ ] Active voice used throughout
- [ ] Present tense maintained
- [ ] Sentences under 26 words
- [ ] No unnecessary words
- [ ] Positive language used

### Formatting
- [ ] UI elements in sentence case and bold
- [ ] Numbers written as numerals
- [ ] Oxford commas used
- [ ] Appropriate list types (numbered vs. bulleted)
- [ ] Correct quotation marks

### Links and References
- [ ] Descriptive link text
- [ ] Proper external reference format
- [ ] Full stops after links (not emails)
- [ ] Email format correct

## Common Mistakes to Avoid

### Language Issues
- ❌ Passive voice: "The form is submitted by clicking the button"
- ❌ Future tense: "The system will process the payment"
- ❌ Nominalizations: "The implementation of the feature"
- ❌ Clipped language: "Click button to submit"

### Formatting Issues
- ❌ Title case: "How To Configure The System"
- ❌ UI elements in caps: "Click the SUBMIT button"
- ❌ Missing Oxford comma: "red, white and blue"
- ❌ Semicolons in simple lists

### Structure Issues
- ❌ Instructions before conditions: "Click OK if you see the dialog"
- ❌ Non-parallel lists: "Save file, editing document, to export data"
- ❌ Preannouncing: "This section will cover the following topics"

## Implementation Notes

### For Writers
1. **Review the Google Developer Documentation Style Guide** for items not covered here
2. **Use our deviations** where specified
3. **When in doubt**, prioritize clarity and user understanding
4. **Test instructions** by following them yourself

### For Reviewers
1. **Check against this handbook** first
2. **Verify user experience** - can someone follow these instructions?
3. **Ensure consistency** with existing documentation
4. **Confirm technical accuracy** with subject matter experts

## Updates and Maintenance

This handbook is a living document. When making updates:

1. **Document changes** with date and reason
2. **Communicate updates** to all writers and reviewers
3. **Update existing content** to match new standards
4. **Provide examples** for new guidelines

---

*Last updated: [Date]*  
*For questions about this handbook, contact the Documentation Team at docs@company.com*