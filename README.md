# [BASE] NODE API
### Minimalist config to a TDD ready API

[ x ] Typescript - Auto   
[ x ] Lint - Fix and display code errors  
[ x ] LintStaged - Test only staged files  
[ x ] Husky - Run test before commit  
[ x ] Commit linter - Force conventional commit format
```
{
  "*.ts": [
    "eslint 'src/**' --fix",
    "npm run test:staged"
  ]
}
```

#### This project is pre-configured to use:

https://www.standardjs.com
https://www.conventionalcommits.org/
https://jestjs.io/docs/pt-BR/api