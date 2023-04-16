# DockerFile ASP.Net Project

this project is prepared to demonstrate the use of docker compose with net6.it include a end point which returns instant time

## Installation

first of all you need to download docker.you can google it.
after that you should install this project to local   

```bash
git clone https://github.com/omerselimgul/aspnetdockercompose.git
```

## Usage
you must build and run this project with docker compose

```bash
docker compose up 
```
! dont forget must be in the path of the file you cloned
this project work with 5000 port so 

# testing

You can test it by sending a request to this url, as a result, it will return you instant time.
http://127.0.0.1:5000/api/get

## Contributing

Pull requests are welcome. For major changes, please open an issue first
to discuss what you would like to change.

## License

[MIT](https://choosealicense.com/licenses/mit/)