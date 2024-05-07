# Tutorial 10 - Timer Future
**Rachel Heningtyas Zanetta Erari - 2206081944 - A**

## 1.2 Understanding How It Works
<img src="image/image-1.png">

From the output, we can see that the async function will operate outside of the main function that invokes it. Therefore, `hey hey` may appear as the output before `howdy!` and `done!` because `hey hey` is outside the async function. The function will continue with the program and execute `println!("hey hey");` while the async function is still waiting for the result from the future.