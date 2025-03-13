# imagineme-mvp

git clone https://github.com/AIRI-Institute/HairFastGAN
cd HairFastGAN
git clone https://huggingface.co/AIRI-Institute/HairFastGAN
cd HairFastGAN && git lfs pull && cd ..
mv HairFastGAN/pretrained_models pretrained_models
mv HairFastGAN/input input
rm -rf HairFastGAN

pip install -r requirements.txt
