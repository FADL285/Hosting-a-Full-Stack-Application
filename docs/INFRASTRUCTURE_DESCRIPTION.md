<div align="center">
    <h2>Hosting a Full-Stack Application</h2>
    <p>
        <a href="http://fadl-udagram.s3-website-us-east-1.amazonaws.com/" target="_blank">Live Demo 🡥</a>
    </p>
</div>

## AWS Infrastructure Diagram

![Pipeline process Diagram](udagram.png)

## Steps

1. User request the app that hosted on S3 ➡ [Link Preview](http://fadl-udagram.s3-website-us-east-1.amazonaws.com/)
![Front-End hosted on AWS](screenshots/app-running-on-s3.png)
![AWS S3 App files From Console](screenshots/s3-from-console.png)

2. Front-End App request Data From Back-End App which hosted on [Elastic Beanstalk](http://udagram-api-dev.eba-43ppftpt.us-east-1.elasticbeanstalk.com/)
![Elastic Beanstalk Status From Console](screenshots/elastic-beanstalk-status.png)
![Elastic Beanstalk Status & Health From CLI](screenshots/elastic-beanstalk-status-health-cli.png)

3. Back-End App request Data From Database which hosted on RDS ➡ (udagram.czsx1o8j0vjs.us-east-1.rds.amazonaws.com)
![Elastic Beanstalk Status From Console](screenshots/rds.png)
