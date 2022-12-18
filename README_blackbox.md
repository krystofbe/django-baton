# blackbox modifications

to-recompile run:

```
cd baton/static/baton/app
npm install
npm run compile
```

copy the baton.min.js file to your project: e.g.

````
cp dist/baton.min.js ../../../../../django/modulu-backend/static/baton/baton.min.js
````
