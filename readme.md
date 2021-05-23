# stack template for complex webapp
a complex app consisting of reactjs frontend, flask backend, mysqldb, redis cache and algolia search engine


#### once executed, exports following to generated stack
- ⚠️  exports from 1st stack, STACK_GITHUB_REPO_URL for reactjs app
- ⚠️  exports from 1st stack, STACK_REACTJS_URL
- ⚠️  exports from 2nd stack, STACK_GITHUB_REPO_URL for flask app
- ⚠️  exports from 2nd stack, STACK_FLASK_URL
- ⚠️  exports from 3rd stack, STACK_REDIS_URL
- ⚠️  exports from 4th stack, STACK_MYSQLDB_URL
- ⚠️  exports from 5th stack, STACK_ALGOLIA_URL


#### once executed, produces following artifacts to generates stack
- ⚠️  artifact from 1st stack, a github repository
- ⚠️  artifact from 1st stack, a gcp cloudrun app server - serving reactjs app
- ⚠️  artifact from 2nd stack, a github repository
- ⚠️  artifact from 2nd stack, a gcp cloudrun app server - serving flask app
- ⚠️  artifact from 3rd stack, a gcp redis instance
- ⚠️  artifact from 4th stack, a gcp mysqldb instance
- ⚠️  artifact from 5th stack, a algolia instance
