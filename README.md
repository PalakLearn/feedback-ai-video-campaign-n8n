# feedback-ai-video-campaign-n8n
Automated campaign video generation from real-time feedback using OpenAI, n8n, and Dynamics 365.
# 📽️ Feedback-Driven AI Video Campaign Automation (n8n)

## 🔍 Objective  
Automate end-to-end video campaign creation based on user feedback using n8n, OpenAI, and Dynamics 365.

## 🛠 Tools Used  
- n8n (open-source workflow builder)  
- OpenAI API (summarization + script writing)  
- Predis.ai / DeepBrain (AI video generation)  
- Microsoft Teams API / WhatsApp API (approval routing)  
- Dynamics 365 Marketing (video email/sms campaign trigger)

## 🔄 Workflow Steps  
1. Receive feedback from survey or webhook  
2. Use OpenAI to summarize and generate a video script  
3. Auto-generate a video using Predis.ai or DeepBrain  
4. Send the video to the marketing manager for approval via Teams/WhatsApp  
5. If approved → Notify via outlook and trigger campaign via Dynamics 365  
6. If rejected → notify with revisions & log feedback via teams
7. Use OpenAI to Generate a new video with fianl feedback from Managers

## 🧩 Files Included  
- `n8n-workflow/feedback-to-video-workflow.json`  
- `prompt-templates/feedback-summary-and-script.txt`  
- `sample-output/ai-video-script.txt`  
- `assets/ai-video-thumbnail.jpg`

## 📈 Results  
- Reduced video turnaround from 3 days to 10 minutes  
- Increased post-launch campaign agility  
- Enabled human + AI approval flow for campaign safety

## 📸 Visuals

<img width="1288" height="204" alt="Screenshot 2025-07-21 183158" src="https://github.com/user-attachments/assets/51abddeb-7000-4e87-8c61-8fc2f73f21bb" />
<img width="1054" height="166" alt="Screenshot 2025-07-21 183318" src="https://github.com/user-attachments/assets/7a52ac42-5b3b-48d2-8a63-2e8e7a7a7039" />
<img width="486" height="848" alt="Screenshot 2025-07-21 183624" src="https://github.com/user-attachments/assets/17d3529b-3361-4db5-a18a-933001bef415" />
<img width="1088" height="277" alt="Screenshot 2025-07-21 183658" src="https://github.com/user-attachments/assets/eb77281a-29f4-448d-93c9-c07a86e874e2" />


## ✍️ Author
Palak Chaturvedi  
[LinkedIn](https://linkedin.com/in/palak-chaturvedi) | [Portfolio](https://www.notion.so/AI-Powered-Marketing-Content-Generator-237080ad24ae80f7bb59dd4d4a1601e2?p=237080ad24ae80388adcdc34c6e46a37&showMoveTo=true)

