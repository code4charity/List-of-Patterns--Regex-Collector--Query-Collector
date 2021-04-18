# List of Patterns / 'Pattern-Collector' 
The* ['Awesome List'](https://github.com/sindresorhus/awesome#contents) of Patterns        \* _(there seems to be nothing better than this draft!)_

 `>Think regularly, think universally, think mathematically<`

## 1. **Reg**ular **Ex**pressions(=Search Patterns=Data format definitions.) 
Regex are most common & most efficient to type. (Despite they are one of the oldest dicsiplines in programming to make sense of data, convert it, clean it or spell-check it. https://en.wikipedia.org/wiki/Regular_expression)

| Common Data Formats | efficient pattern (*raw with typos, if that's still unique*) | *replace* (*correction*) |
| --: | :-: | :--|  
|Postalcodes |||
|ISBN |||

| Hashes, Public Keys, Signatures | pattern | *replace* |
| --: | :-: | :--|  
| MD6 |||
| *MD5*|||
| SHA256, Bitcoin, ... |||

| convert | pattern | replace |
| --: | :-: | :--|  
MarkDown links to HTML links |`\[([^\]]*)\]\(([^\)]*)\)`|`<a href="$2">$1</a>`|
List of Patterns to Javascript |\|\`([^\`]\*)\`\|\`([^\`]\*)\`\||`replace ($1,"$2");`|

[Full List of 1000's](https://github.com/code4charity/List-of-Patterns--Regex-Collector--Query-Collector/edit/main/README.md#All-Regex

## 2. Preprocessing Patterns: 
A List of Patterns / Regex can automatically be analyzed for similarities and thus be combined in a preprocessing step. 
I.e. Preprocessing might Reduce Input data by 90% already in half the time. 

## 3. Semantic patterns:
### Human Grammar / Natural language processing. 
https://github.com/edobashira/speech-language-processing#readme

## 4. Querying Public Databases & the internet.

#### Semantic web
#### WikiData
#### Google 
#### AWS public databases

## 5. Merging the above disciplines    

## 6. Human work VS machine learning

# All-Regex
#### Others Lists  // potential Sources: 
#### Compare:  https://www.mulesoft.com/exchange/?type=connector&view=list   (>10000 'enterprise patterns')
