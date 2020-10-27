the repo contain the tests for load API.

for install the artillery tool run the command
```
npm install -D artillery
```
after run the command for checking version
```
$(npm bin)/artillery dino
````
you should receive the image with dino

run the load scenario from yml with command
```
$(npm bin)/artillery run SCENARIO_FILE.yml
```
run the tests and save results into the txt file
```
$(npm bin)/artillery run SCENARIO_FILE.yml -o results.txt
```
