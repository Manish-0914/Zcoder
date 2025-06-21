
# ZCoder

An interactive coding community platform to practise and scale up your skills.

## 🔧 How to Run Locally

### first clone the repository
``` bash
git clone https://github.com/vijay-kumar-79/ZCoder.git
cd ZCoder
```
### run backend
``` bash
cd backend
npm i 
nodemon index.js
```
Create a file named `.env` in the `backend` folder (at the same level as `index.js`) with the following content:
```
GROQ_API_KEY = your_api_key
```
(Create your own key at https://console.groq.com/keys)

### run frontend
then open a new terminal and
```bash
cd frontend
npm i
npm run dev
```
also create a new file called .env in the frontend folder at the same level of src,public. The format for it is
```
REACT_APP_API_URL = https://alfa-leetcode-api.onrender.com
REACT_APP_BACKEND_URL = http://localhost:5000
REACT_APP_JUDGE = https://emkc.org/api/v2/piston/execute
```
Then visit http://localhost:3000

