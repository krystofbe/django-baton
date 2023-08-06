Blackbox Modifications for Django-Baton Django Admin
----------------------------------------------------

To recompile, run the following command. After recompiling, set the `$PROJECT_PATH` environment variable to the path of your project, replacing `modulu-backend` with your project name. Finally, copy the `baton.min.js` file to your project's static directory.


````
#!/bin/bash

export PROJECT_PATH=../django/modulu-backend
(cd baton/static/baton/app && yarn && yarn compile)
cp baton/static/baton/app/dist/baton.min.js $PROJECT_PATH/static/baton/baton.min.js

```

