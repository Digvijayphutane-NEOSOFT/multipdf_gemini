# multipdf_gemini

To run globly : 
1. Run streamlit : streamlit run file name
2. use ngrok
3. install ngrok : curl -s https://ngrok-agent.s3.amazonaws.com/ngrok.asc \
	| sudo tee /etc/apt/trusted.gpg.d/ngrok.asc >/dev/null \
	&& echo "deb https://ngrok-agent.s3.amazonaws.com buster main" \
	| sudo tee /etc/apt/sources.list.d/ngrok.list \
	&& sudo apt update \
	&& sudo apt install ngrok
4. configure ngrok : ngrok authtoken <ngrok api key> 
5. ngrok http 8501
