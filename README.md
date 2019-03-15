# python_flask_sample
  Tutorials of flask with python

  Flask is useed tu aplicación web WSGI ligero.
  Flask does not impose any dependence or design of the project. It is the responsibility of the developer to choose the tools and l    	  ibraries that he wishes to use. The community provides many extensions that facilitate the addition of new functions.
  

# Install Matraz

  You must install with pip 
		pip instalar -U matraz
    
# Example:
  from flask import Flask

  app = Flask(__name__)

  @app.route('/')
  def hello():
      return 'Hello, World!'
