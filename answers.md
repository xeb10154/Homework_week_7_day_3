### Q1. Which view is rendered more than once?
ContinentView is rendered more than once. This is because of the following function is called within a forEach loop within the ContinentsListView.

```
continentView.render();
```
### Q2. Which views are nested in which other view?
ContinentView is nested within ContinentsListView.

### Q3. What are the benefits of using nested reusable views in this way?
There is less publish and subscribe function calls as data is passed between views without going through PubSub (I think).
