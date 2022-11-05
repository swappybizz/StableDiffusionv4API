Use this to make your own Stable Diffusion api
Instructions: 
1. Install dependencies from Requirements.txt
2. Activate the proper environment 
3. use Swagger UI by using /docs at the end of the address on ur addressbar on the port the app is running. eg . http://127.0.0.1:8000/docs#
4. Test the app
5. If you want to expose the endpoint from your local machine ( good luck!!) use ngrok (optional)
6. Use this for good and betterment of humanity. I am watching you :)

Run : uvicorn api:app 
Dev Run : uvicorn api:app --reload      // This watches changes in code 

Requirements:
CUDA supported GPU 
8GB RAM

If you want to deploy it someplace, good luck with the free teir limits but 
1. Use Containers
2. If not generate requirement.txt file , Procfile etc 
3. Gunicorn workers 