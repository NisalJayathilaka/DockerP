docker run -d \
  -p 3000:5173 \
  --name react-app \
  -v /app/node_modules \
  -v ${PWD}:/app \
  -e CHOKIDAR_USEPOLLING=true \
  357a4b130aeb



  