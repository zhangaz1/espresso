![](https://i.ibb.co/CV9Mnhj/espresso.png)

deno minimal web freamework

# Getting Start
```javascript
import { Application } from ""https://deno.land/x/espresso/mod.ts";
const app = new Application();

app.get("/", context => {
  context.send("Hello From Deno !");
});

app.start(80)
```