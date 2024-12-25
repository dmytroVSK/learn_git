1. git rev-parse --short HEAD >>> get current hash of commit
2. git rev-parse HEAD~ (HEAD~1) >>> get commit of first parent
3. git rev-parse HEAD~~ (HEAD~2) >>> get commit of second parent
4. git cat-file -p hash >>> show parents of commit
5. git rev-parse --short HEAD^2 >>> switch to another parent and get current commit aka HEAD
6. git rev-parse --short HEAD^2~ (HEAD^2^) >>> switch to another parent and get commit of 1st parent of its aka HEAD~1 e.g. HEAD^2~2
