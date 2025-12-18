# Speech-to-Text-Converter-Using-AWS
The Sound to Text Converter Using AWS is a cloud-based application developed during industrial training at Ardent Computech Pvt. Ltd. The project focuses on building an automated speech-to-text system using Amazon Web Services (AWS) that converts spoken audio files into accurate written text with minimal manual intervention.
This system leverages AWS’s scalable microservices architecture to ensure high availability, accuracy, and cost efficiency, making it suitable for real-world applications such as transcription, subtitles generation, accessibility tools, and audio content analysis.

🛠️ Technologies & AWS Services Used
    Amazon S3 – Stores uploaded audio files securely,
    Amazon CloudFront – Distributes audio files globally using CDN for low latency,
    Amazon Transcribe – Converts speech into text using automatic speech recognition (ASR) &
    Amazon EC2 – Runs a microservice that automates the end-to-end transcription workflow

🔄 Project Workflow
    Audio files are uploaded to an Amazon S3 bucket,
    CloudFront distributes the audio files globally (optional but recommended),
    Amazon Transcribe processes the audio and generates accurate text output, 
    An EC2-based microservice:
        Monitors the S3 bucket for new uploads,
        Triggers transcription jobs,
        Retrieves and stores transcription results.

✨ Key Features
    Automated speech-to-text conversion,
    Scalable and cloud-native architecture,
    Supports batch transcription,
    Secure and reliable AWS infrastructure,
    Cost-effective pay-as-you-go model &
    Improved accessibility through text-based output.

🎯 Project Outcomes

Fully automated transcription pipeline,
Centralized storage and easy retrieval of audio and text data,
Reduced manual effort and faster processing time,
Scalable solution capable of handling large audio volumes &
Enhanced usability of audio content through searchable text.


https://github.com/user-attachments/assets/93b90b24-4954-4c49-b765-7e8e1161a2ec
