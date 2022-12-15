# Vladimir Moskalenko
---
## Contact
 ##### __Tg: @mvssssss | Phone: +375(33)9038066 | email: moskalenko_vldmr@outlook.com__
---
## Education
##### [2018-2022] Vitebsk State University
##### Bachelor of Computer Security
---
 ## Knowledge
 * HTML+CSS - basic
 * C++ - basic
 * C# - basic
 * JS - basic
---
## Languages
* Russian - native
* English - A2
---
# Code Exemple
---
function getLengthOfMissingArray(arrayOfArrays) {
  const lengths = (arrayOfArrays || [])
    .map(a => a ? a.length : 0)
    .sort((a, b) => a - b)
  
  if (lengths.includes(0)) {
    return 0
  }

  for (let i = 0; i < lengths.length - 1; i++) {
    if (lengths[i] + 1 !== lengths[i + 1]) {
      return lengths[i] + 1
    }
  }

  return 0
}
---