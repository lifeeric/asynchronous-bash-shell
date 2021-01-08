# Execute your bash code asynchronously


This is trick using while loop with `sleep` command, anything can be done inside while with the sleep
```bash
while :
do
  clear;
  tree .git/
  sleep 1
done
```
  
  
  open two terminal and run the above code in one terminal and leave. head over to another terminal and remove some files from the `git` and see what happens
  
  ```bash
  rm .git/hooks
  ```
  
  ![image](https://i.ibb.co/zhY66Wj/asynbash.gif)
