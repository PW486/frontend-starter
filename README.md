# express-ts

> 🚀 Quick Start BackEnd (Node/TypeScript/Express/TypeORM)

## Key Points

1. Use rebase autosquash `git rebase -i --autosquash develop`
2. Remove removed branches `` git fetch -p && for branch in `git branch -vv --no-color | grep ': gone]' | awk '{print $1}'`; do git branch -D $branch; done ``
3. Watch concurrently `"watch": "concurrently -k -p \"[{name}]\" -n \"TypeScript,Node\" -c \"cyan.bold,green.bold\" \"npm run watch-ts\" \"npm run watch-node\""`
4. Check unused packages `npm i -g depcheck`
5. Check outdated packages `npm i -g npm-check-updates`
6. Check security vulnerabilities `npm i -g snyk`

## TODO

- [ ] express-validator / class-validator
- [ ] error handler
- [ ] API Implement (board-get/post/put/patch/delete)
- [ ] multer (board-post/put)
- [ ] jwt auth (user)
- [ ] jest init