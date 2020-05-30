We will create a simple application with java

we will use the images created here java-example


#  Build
```ruby
docker build -t java:latest -f Dockerfile .
```
# Run
```ruby
docker run -d -p 5000:9080 --name myapp oktaysavdi/java:latest
```
# Call
```ruby
curl http://localhost:5000/webapp
```
