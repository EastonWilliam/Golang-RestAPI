
# REST API to Execute Shell Commands

- It is a golang REST API application to execute shell command from payload
- It is not recommended - Just for learning purpose



## Usage

```bash



# go rest-api-to-exec-shell dir
cd rest-api-to-exec-shell

# run

go run main.go


# sample payload to list files and folder under /home/akilan/Desktop dir
{
    "command": "ls",
    "arguments": ["-l","/home/akilan/Desktop"]
}

# Sample response
{
    "Msg": "total 4\ndrwxrwxr-x 35 akilan akilan 4096 Nov 18 19:55 devops-work\n"
}
```

## Contributing

Pull requests are welcome. For major changes, please open an issue first to discuss what you would like to change.
