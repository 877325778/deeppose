deeppose
========
# Data preparation

    $ bash scripts/downloader.sh

This script downloads FLIC-full dataset (http://vision.grasp.upenn.edu/cgi-bin/index.php?n=VideoLearning.FLIC) and perform cropping regions of human and save poses as numpy files into FLIC-full directory.

# Start training

    $ bash scripts/train.sh ModelName

where the "ModelName" is the directory name in models dir you want to train with architecture described in.