# Using Custom Models in Cursor IDE

## Prerequisites
- **API Endpoint**: You'll need the endpoint (base URL) and an API key for the model you intend to use.Any service compatible with OpenAI’s API can be integrated. For Groq, the endpoint is:
  ```
  https://api.groq.com/openai/v1
  ```
- **API Key**: Obtain an API key for the model provider (Groq, OpenAI, etc.).

## Step-by-Step Configuration

### 1. Open Cursor Settings
- Go to the Settings section in Cursor IDE. (Refer to the settings screen in the accompanying image).
![Alt text](https://raw.githubusercontent.com/bilal77511/custom-models-in-cursor-IDE/refs/heads/main/pics/settings.png)


### 2. Disable Current Models
- Disable any pre-enabled models in the list to avoid conflicts.
![Alt text](https://raw.githubusercontent.com/bilal77511/custom-models-in-cursor-IDE/refs/heads/main/pics/disable.png)
### 3. Add Your Custom Model
- Click on Add Model to configure a new model.
![Alt text](https://raw.githubusercontent.com/bilal77511/custom-models-in-cursor-IDE/refs/heads/main/pics/model.png)


### 4. Override OpenAI Base URL
- Enable the Override OpenAI Base URL option.
- Enter the custom model's base URL. For Groq, use:
  ```
  https://api.groq.com/openai/v1
  ```
- Enter your API Key obtained from the model provider.
![Alt text](https://raw.githubusercontent.com/bilal77511/custom-models-in-cursor-IDE/refs/heads/main/pics/override.png)

### 5. Verify and Activate
- Click on Verify to test the connection. If all goes well, the model should now be activated and ready for use in Cursor IDE.

## Installing Cursor on Ubuntu
To learn how to install Cursor IDE on Ubuntu, follow this installation guide for Cursor on Ubuntu.  
[Installing and Troubleshooting Cursor on Ubuntu GitHub](https://github.com/bilal77511/Cursor-on-Ubuntu)  
[Installing and Troubleshooting Cursor on Ubuntu Medium](https://medium.com/@bilal77511/installing-and-troubleshooting-cursor-on-ubuntu-aa51d36cac66)
## Stay Connected
If you found this guide helpful, feel free to connect me on [LinkedIn](https://www.linkedin.com/in/muhammad-bilal-a75782280/)
