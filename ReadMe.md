The project is inspired the work of [kshitizrimal](https://github.com/kshitizrimal/Cash-Recog-Project).
The aim like the original project is to help the visually impaired with the management of their curreny notes.
This repositry specifically aims to addressd the problem in Pakistan.


# Requirements

## Core
- AI enabled identification of currency notes
- Real time detection of notes:
	- Type
	- Number
	- Total
- Voice enabled Feedback
## Extended
- Fraud Detection of Notes

# Break down 

## Cash Detector

- [x] Gather dataset online (Scrap)
	- Scrapped data from internet
	- Recorded custom video from mobile 
- [x] Capture dataset images for complex tasks
- [x] Balanced dataset of around 3000 images 
- [x] Label datasets using labellimg
- [] Train and Desgin Model using Pytorch:
	- [] Yolov5
- [] Test model on computer
- [] Convert model to tensorflow lite
 
## Text To Speech
- [] R&D available  modules

## Mobile App based UI

- [] Create basic UI
- [] Integrate AI model
- [] Enable Voice Interaction

