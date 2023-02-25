# trmihnle film streaming

A free movie and web series streaming application built with microservices architecture that allows you to watch movies and web series directly in your browser.

## Runing service in development
- Booting a microservice <br>
    Node.js is being used for this microservices. <br> 
    > npm install <br>
    > npm run start:dev
- Booting the application <br>
    > cd film-streaming <br>
    > docker-compose up --build <br>
    
Now, with the trmihnle-film-streaming application running, open your browser and navigate to
http://localhost:4000 to see FlixTube’s main page.

Take some time to explore FlixTube’s UI: <br>
> 1. Navigate to the upload page.<br>
> 2. Upload a video. <br>
> 3. Navigate back to the main page to see the uploaded video in the list. <br>
> 4. Click the video to play it. <br>

Can do that by pressing Ctrl-C in the terminal where Docker Compose is running and by then invoking:  <br>
> docker-compose down <br>

