# fieldeocr
Tool to help with OCR proofreading of Adele Marion Fielde works and al.

# Installation
todo

# Usage
todo

# Contributing
There is 4 part in this project :
- Post-proofreading help is a small project. It is used after proofreading a page to make small corrections.
  - Checking newlines and ```<br/>``` presence
- Current post-ocr processing consists of :
  - Automatically replacing known pattern errors
  - Adding Swatow Gap automatically
- Advanced post-ocr processing consists of :
  - Learning from previously done proofreading
  - Helping in processing new pages by suggesting candidates
- Others tools
  - Text converter ia6 <=> iã <=> iă
  - Search tool
## Post-proofreading
- Remove all end-of-line/new-line
- Add new-line in front of every ```{{swatow entry|```
- Add new-line in front of every ```<section begin=```
- Visual check for new-lines and ```<br/>``` presence

## Current Post-OCR processing
## Advanced Post-OCR processing
