# Speech transcription
The template defines 
- Source and destination S3 buckets to handle audio and transcription files
- AWS Lambda function to administrate Amazon Transcribe service
- Roles and Policies required for the application

By default source bucket for audio files named *tweexy-voice*. 
The destination one (to hold transcription files) is *tweexy-transcriptions*. 
Both could be renamed during the template import.  
  

Feel free to [launch the stack](https://console.aws.amazon.com/cloudformation/home?#/stacks/new?stackName=speech_transcription&templateURL=https://github.com/dtcimbal/aws-cloudformation-templates/blob/master/aws/transcribe/transcribe-voice/template.yml)
with AWS CloudFormation
