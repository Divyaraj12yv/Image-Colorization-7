# Task 7:-
# Time-Based Historical Image Colorization Description:


🎯 Objectives


Automatically classify the historical era of grayscale images

Apply colorization techniques with era-specific color palettes

Provide a GUI where users can:

Upload grayscale photographs

View time-aware colorized results

Override the detected era manually if desired


🧠 Models and Techniques Used :-


Image Era Classification:

Custom CNN classifier or pre-trained feature extractor (ResNet, VGG)

Trained on labeled historical datasets categorized by decade/era

Colorization Module:

Adapted DeOldify or a custom U-Net based model

Applies different learned or hand-tuned color palettes based on the detected/selected era

Era-Specific Palettes:


1900s: Sepia tones, pale reds

1920s: Faded browns and greens

1940s–50s: Muted colors with uniform tones

1970s: Warm yellows and reds


🧪 Dataset :

Training:

Historical images sorted by era (e.g., 1900s, 1920s, 1950s)

Public sources such as:

WWII Archive

Flickr Commons

Kaggle Historical Image Datasets

Preprocessing:

Resized to 256x256

Normalized for classification and colorization inputs

📊 Evaluation :-

Era Classification Accuracy: ~85% on test set

Colorization Realism (Subjective): Compared against real hand-colored historical photos

User Control: Users can override era prediction to refine color output


📌 Future Improvements :-

Add fine-grained palette editing tools

Expand to more eras (e.g., 1880s, 1990s)

Improve era detection using metadata or image context







