<h1>IN226045502_FASTAPI</h1>

<p>
This repository contains FastAPI internship assignment tasks demonstrating how to build REST APIs using 
<strong>Python FastAPI</strong>. The project shows basic API creation, request handling, and running a backend server using Uvicorn.
</p>

<hr>

<h2>Project Overview</h2>

<p>The purpose of this project is to understand the core concepts of FastAPI including:</p>

<ul>
<li>Building REST APIs</li>
<li>Creating API routes</li>
<li>Handling HTTP requests</li>
<li>Running an API server using Uvicorn</li>
<li>Testing APIs using browser or tools like Postman</li>
</ul>

<hr>

<h2>Technologies Used</h2>

<ul>
<li>Python</li>
<li>FastAPI</li>
<li>Uvicorn (ASGI server)</li>
<li>Git & GitHub</li>
</ul>

<hr>

<h2>Project Structure</h2>

<pre>
IN226045502_FASTAPI
│
├── main.py              # FastAPI application
├── requirements.txt     # Project dependencies
├── README.md            # Project documentation
└── other task files
</pre>

<hr>

<h2>Installation</h2>

<p>Clone the repository</p>

<pre>
git clone https://github.com/AlwalaShivakumar/IN226045502_FASTAPI.git
</pre>

<p>Move into the project directory</p>

<pre>
cd IN226045502_FASTAPI
</pre>

<p>Create a virtual environment</p>

<pre>
python -m venv venv
</pre>

<p>Activate the virtual environment</p>

<p><strong>Windows</strong></p>

<pre>
venv\Scripts\activate
</pre>

<p><strong>Mac / Linux</strong></p>

<pre>
source venv/bin/activate
</pre>

<p>Install dependencies</p>

<pre>
pip install -r requirements.txt
</pre>

<hr>

<h2>Run the Application</h2>

<p>Start the FastAPI server using the command below:</p>

<pre>
uvicorn main:app --reload
</pre>

<p>The server will run at:</p>

<pre>
http://127.0.0.1:8000
</pre>

<hr>

<h2>API Documentation</h2>

<p>FastAPI automatically generates interactive documentation.</p>

<p><strong>Swagger UI</strong></p>

<pre>
http://127.0.0.1:8000/docs
</pre>

<p><strong>ReDoc</strong></p>

<pre>
http://127.0.0.1:8000/redoc
</pre>

<hr>

<h2>Example Endpoint</h2>

<p><strong>GET Request</strong></p>

<pre>
GET /
</pre>

<p><strong>Response</strong></p>

<pre>
{
  "message": "Hello World"
}
</pre>

<hr>

<h2>Screenshots</h2>

<p>Add screenshots of:</p>

<ul>
<li>Running server</li>
<li>Swagger API documentation</li>
<li>API testing results</li>
</ul>

<hr>

<h2>Author</h2>

<p>
<strong>Shiva Kumar Alwala</strong><br>
GitHub: 
<a href="https://github.com/AlwalaShivakumar">
https://github.com/AlwalaShivakumar
</a>
</p>

<hr>

<h2>License</h2>

<p>This project is created for educational and internship purposes.</p>
