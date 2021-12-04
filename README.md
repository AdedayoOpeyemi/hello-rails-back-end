![](https://img.shields.io/badge/Microverse-blueviolet)

### Hello Rails Back End

This is a rails web api. The database store greetings and the api returns a random api for each request. Then the react [project](https://github.com/AdedayoOpeyemi/hello-react-front-end) uses a api fetch request to display the greeting.

### React Project

You also need to download and run a second project that works as the front end, just follow this link [Front End Project](https://github.com/AdedayoOpeyemi/hello-react-front-end)

### Prerequisites

- Windows, Mac, or Linux machine 

- Web browser other than Internet Explorer

- Postgres installed and set it up [see how](https://www.digitalocean.com/community/tutorials/how-to-install-postgresql-on-ubuntu-20-04-quickstart)


## Getting Started

To get a local copy up and running follow these simple example steps.

- First, you need to fork the repository [Hello Rails Back End](https://github.com/AdedayoOpeyemi/hello-rails-back-end)


- Then you clone the repository to your pc using, the command on your terminal:

```
git clone https://github.com/AdedayoOpeyemi/hello-rails-back-end.git
```

- Select the folder
```
`cd hello-rails-back-end`

### Setup

Install gems with:

```
bundle install
```

Then use the following code on your terminal:

```
run yarn install
```
Setup database with:

```
rails db:migrate
```

If you get and error while creating the database then you have to install Postgres, follow the steps [here](https://www.digitalocean.com/community/tutorials/how-to-install-postgresql-on-ubuntu-20-04-quickstart), once installed you only need to create a user and the database.

To create the database type on your terminal:
```
sudo -u postgres psql
```
Then type:
```
createdb db/developmentgreetingapi
```


### Usage

Start server with:

```
rails server
```
This will create the server on port 3050, leaving the port 3000 for the react project free

### Build With

- Ruby 
- Rails
- Postgres

### API Features

Get access to a random greeting by accesing to:
```
http://localhost:3050/api/v1/greetings
```

**Authors**

👤 **Opeyemi Oyelesi**

- GitHub: [@AdedayoOpeyemi](https://github.com/AdedayoOpeyemi )

- Twitter: [@oyelesiopy](https://twitter.com/oyelesiopy )

- LinkedIn: [Opeyemi Oyelesi](https://www.linkedin.com/in/Opeyemioyelesi/)
​

## 🤝 Contributing

Contributions, issues, and feature requests are welcome!

## Show your support


Give a ⭐️ if you like this project!


## Acknowledgments

- Microverse ( https://www.microverse.org/ )

## 📝 License
