Welcome to your new dbt project!

### How to run this project 
### About the project
This project is based in [dbt starter project](https://github.com/dbt-labs/dbt-starter-project) (generated by running `dbt init`)
Try running the following commands:
- dbt run
- dbt test

A project includes the following files: 
- dbt_project.yml: file used to configure the dbt project. If you are using dbt locally, make sure the profile here matches the one setup during installation in ~/.dbt/profiles.yml
- *.yml files under folders models, data, macros: documentation files
- csv files in the data folder: these will be our sources, files described above
- Files inside folder models: The sql files contain the scripts to run our models, this will cover staging, core and a datamarts models. At the end, these models will follow this structure: 
