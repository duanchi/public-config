# Public-Config 

> The config files for all applications & libraries

All config files must named in forms below:

> `read` {APPLICATION_KEY}\_{ENVIRONMENT}\_{SCOPE}.ini

> `segment` {APPLICATION_KEY}\_{ENVIRONMENT}\_{SCOPE}.ini.segment

`.segment` file will merged by {config}_base.ini.

It will load {APPLICATION_KEY}\_base\_{SCOPE}.ini while {APPLICATION_KEY}\_{ENVIRONMENT}\_{SCOPE}.ini not exist.