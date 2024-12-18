This repository demonstrates a subtle Firebase Firestore bug where data fails to persist despite a successful `set()` operation. The problem arises from a missing composite index. The `bug.js` file contains the problematic code, while `bugSolution.js` shows how to resolve the issue by creating the necessary index in the Firestore console.  The issue is specifically related to querying data based on multiple fields when those fields aren't indexed correctly.