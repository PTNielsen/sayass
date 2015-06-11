sayaas.rb includes the object, SaySomethingAPI, while server.rb is the server file which is utilizing Sinatra and holds a single endpoint ("/speak").

In order to customize the voice and text you'd like to hear, please enter those desired values as parameters (curl -X GET -d"voice=...&text=...").  Otherwise, if parameters are not provided, the server will default to the voice "Alex" and the text "Add a 'voice' parameter to hear a different voice and a 'text' parameter if you'd like for me to say something else."