# git commit - m and git commit -am me diffrence 
🔹 git commit -m "message"

Sirf staged files ko commit karta hai

Pehle git add karna mandatory hai

Example:

git add file.txt
git commit -m "added file"

🔹 git commit -am "message"

Modified (already tracked) files ko:

Automatically stage karta hai

Aur commit bhi kar deta hai

New (untracked) files par kaam nahi karta

Example:

git commit -am "updated file"

⭐ Short Interview Answer (BEST)

git commit -m staged files ko commit karta hai, jabki git commit -am modified tracked files ko automatically stage karke commit karta hai.

🧠 One-line yaad rakhna
-m  = commit staged files
-am = add + commit (only tracked files)

⚠️ Common Interview Trap

Agar tum bol do:

“git commit -am new file ko commit kar deta hai”

❌ Wrong ho jayega
