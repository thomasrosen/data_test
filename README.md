# data_test

Use something like

```
mkdir sun_42
&& cd sun_42/
&& git clone https://github.com/thomasrosen/data_test.git --branch "TEMPLATE"
&& cd data_test
&& git checkout -b sun_42
&& echo "sun_42" >> sun_42.yml
&& git add --all
&& git commit -m "test commit sun_42"
&& git push --set-upstream origin sun_42
&& cd ../../
&& rm -Rf sun_42/
```

to push changed to a new branch without ownloading everything already in data.
