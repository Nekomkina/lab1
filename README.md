# node-aseko5
# Run

$ git clone https://github.com/Nekomkina/lab1

$ npm i

# Usage example:
**CLI tool accept 3 options (short alias and full name):**

-i, --input: an input file

-o, --output: an output file

-a, --action: an action find/add

**Find number 1.txt to 2.txt :**

$ node finder.js -i "1.txt" -o "2.txt" -a find

**Matrix addition "3.txt" to stdout:**

$ node finder.js  -i "3.txt" -a add

**Find number stdin to stdout:**

$ node finder.js -a find
[Edit on StackBlitz ⚡️](https://stackblitz.com/edit/node-aseko5)
