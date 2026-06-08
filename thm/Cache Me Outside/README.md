# Cache Me Outside

**Platform:** TryHackMe
**Difficulty:** Medium
**Tags:** OSINT, Web

## Summary
OSINT training and information gathering.

---

## TASK 1
```
Go to `https://www.komoot.com/user/5667624959835`. 
The target's name is located somewhere on the profile.
```

## TASK 2
```
Go to his GitHub account and look into his only repository. 
Check the initial commit and append `.patch` to the URL. 
The answer is hidden in the commit metadata.
```

## TASK 3
*(I had a problem with this one)*
```
Using the discovered email, check if the target has an autoresponder enabled. 
The answer is in the automated reply.
```

## TASK 4 
```
Check if the username `jiml33t` is reused elsewhere. 
A Google search leads to his Instagram (`https://www.instagram.com/jiml33t/`). 
Click the Threads link in his bio. A photo posted there reveals a store named `irigatii.ro`. 
Search Google for this store to find the target's location.
```

## TASK 5
```
Search for a French supermarket in the identified city and look for a tram station nearby.
```
---

## Key Takeaways
- **OPSEC Failure & Username Reuse** (Instagram, GitHub)
- **Metadata Leakage** (commit `.patch` header)
- **Auto-Responder** (Gmail)

---


