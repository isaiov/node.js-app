1. https://github.com/isaiov/node.js-app
2. git clone https://github.com/isaiov/node.js-app.git
3. docker build -t nodejs-demoapp:4.9.9 -f build/Dockerfile .
4. docker run -d -p 3000:3000 --name nodejs-demoapp nodejs-demoapp:4.9.9
5. local: http://localhost:3000
