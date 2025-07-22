FROM orbslam3:latest

 ENV DEBIAN_FRONTEND=noninteractive

 # install torch dependencies
RUN python3 -m pip install torch torchvision torchaudio \
    fifty regex tqdm

# install clip 
RUN python3 -m pip install git+https://github.com/openai/CLIP.git



