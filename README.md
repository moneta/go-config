# go-config
Provides a standard configuration interface for golang projects

# Usage
Put your configuration file under the folder specified by the environment variables `CURRENT_CONFIG_NAME` and `CURRENT_CONFIG_PATH`

# Example
```sh
export CURRENT_CONFIG_NAME=config
export CURRENT_CONFIG_PATH=./config 
```

This is a sample of `config/yaml` file:
```
env:
    DB_CONNECTION_STRING: 'postgress://user_name:password@host:5432/postgres'
    SOME_SETTING: value
```