
<h1 align="center">
  <br>
 <a href="https://imgbb.com/"><img src="https://i.ibb.co/Q7VtNcD/blitz-removebg-preview.png" alt="blitz-removebg-preview" width=100 border="0"></a>
  <br>
  blitz
  <br>
</h1>

<h4 align="center">A simple load testing application built in Django.</h4>

<p align="center">
</p>

<p align="center">
  <a href="#key-features">Key Features</a> •
  <a href="#how-to-use">How To Use</a> •
  <a href="#credits">Credits</a> •
  <a href="#license">License</a>
</p>


## Key Features
-  Measure response time, throughput, error rate, and latency of your APIs.
- Measure network usage of your APIs during load testing to identify potential bottlenecks.
- Analyze HTTP response code distribution to identify areas for improvement in API functionality.
- Track average, median, maximum and minimum response times for a more comprehensive understanding of API performance.
- Monitor your CPU and memory usage while performing load tests.

## How To Use

### Initial setup
To clone and run this application, you'll need [Git](https://git-scm.com) , [Python 3](https://www.python.org/downloads/) and [virtualenv](https://pypi.org/project/virtualenv/) installed on your computer. From your command line:

```bash
# Clone this repository
$ git clone git@github.com:michael-awe/app-load-testing-ag.git

# Go into the repository
$ cd blitz

# Install dependencies
$ python3 -m venv env
$ source env/bin/activate
$ pip install -r requirements.txt
$ python manage.py makemigrations && python manage.py migrate

```

### Running the application
After activating your virtual environment,
```bash
# Run the app
$ python manage.py runserver
```
Navigate to https://127.0.0.1:8000 in your browser to use the app

## Credits

This software uses the following open source packages:

- [Django](https://www.djangoproject.com/)
- [Chart.js](https://www.chartjs.org/)

## License

This project is licensed under the **MIT License**, which grants users the freedom to modify, distribute, and use the code for both personal and commercial purposes.

---

### Disclaimer

This load testing package is intended solely for lawful educational, research, and testing purposes. Users are explicitly forbidden from utilizing it for malicious or harmful activities such as unauthorized stress tests, Denial-of-Service (DoS) attacks, or any other actions targeted at disrupting the operation of third-party systems.

Note that any damage or impairment caused to your own systems as a result of using this package is solely your responsibility. The author explicitly disclaims all liability for any consequences, direct or indirect, that may occur as a result of using this package. 

Also, using this package improperly or in violation of applicable laws might expose you to legal consequences, including civil and criminal liability. The author will not be responsible for any such legal repercussions, nor for any damages, harm, or adverse outcomes alleged to result from directly or indirectly using this package.

> GitHub [@michael-awe](https://github.com/michaelawe) &nbsp;&middot;&nbsp;

