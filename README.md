How to run:
```
cf-agent -K -f `pwd`/promises.cf -Dgroup_test | sed -r 's/R: //' | json_pp
```
