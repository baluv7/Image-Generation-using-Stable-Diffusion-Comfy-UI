# Image-Generation-using-Stable-Diffusion-Comfy-UI
A user-friendly AI image generation system that converts text prompts into high-quality images using Stable Diffusion and ComfyUI. Designed for accessibility and efficiency, this project simplifies AI-driven creativity for both technical and non-technical users.

✨ Features
Text-to-Image Generation: Create visuals from textual prompts.
Real-Time Updates: Generate new images without refreshing the page.
Optimized Performance: Faster processing with advanced samplers and CUDA GPU support.
Customizable Parameters: Adjust settings for better output control.

🛠️ Installation & Setup

Prerequisites

Hardware Requirements :

CPU: Modern multi-core processor (Intel/AMD).
RAM: 8GB or higher.
GPU (Recommended): NVIDIA GPU with ≥4GB VRAM for accelerated performance.
Software Requirements :

ComfyUI: Download ComfyUI (https://github.com/comfyanonymous/ComfyUI)
Stable Diffusion Model: Download v1-5-pruned-emaonly-fp16.safetensors (https://huggingface.co/Comfy-Org/stable-diffusion-v15-archive/blob/main/v1-5-pruned-emaonly-fp16.safetensors)

🚀 Getting Started

Step 1: Extract ComfyUI
Download the ComfyUI_windows_portable.zip file from the ComfyUI GitHub. (https://github.com/comfyanonymous/ComfyUI)
Extract the ZIP file to a folder of your choice.
Step 2: Place the Stable Diffusion Model
Navigate to the extracted folder:
ComfyUI_windows_portable → ComfyUI → models → checkpoints
Place the downloaded Stable Diffusion model (v1-5-pruned-emaonly-fp16.safetensors) into the checkpoints folder.
Step 3: Run ComfyUI
Go back to the ComfyUI_windows_portable directory.
Choose the appropriate batch file:
For GPU (NVIDIA): Double-click run_nvidia_gpu.bat
(Recommended for faster performance)
For CPU-only: Double-click run_cpu.bat
Wait for the server to start. A browser window will open automatically at http://127.0.0.1:8188.

🖼️ Usage
Enter a Prompt: Type your text description in the input field (e.g., "A mystical waterfall in a tropical rainforest").
Generate Image: Click "Generate" to create the image.
Adjust Parameters (Optional): Modify sampling steps, CFG scale, or negative prompts for better results.
Download: Save the generated image to your device.

📜 References
ComfyUI GitHub Repository (https://github.com/comfyanonymous/ComfyUI)
Stable Diffusion Documentation (https://huggingface.co/CompVis/stable-diffusion)

🙏 Acknowledgments
Special thanks to the mentors for their guidance during this project. Developed under the Internship on AI by Microsoft, SAP, Edunet Foundation and AICTE.
