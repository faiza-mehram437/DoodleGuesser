
🦉 AI Doodle Guesser
Draw anything, and Ollie the Owl guesses what it is, live, as you draw.

▶️ Play it here
✨ What it does
🎨 Free Draw: draw anything; Ollie shows his top 3 guesses with live confidence bars
🎯 Challenge mode: "Can you draw a cat?" 6 rounds, 20 seconds each, earn ⭐ stars
🧠 Knows 345 things: animals, food, vehicles, toys, nature, shapes and more
🗣️ Child voice: Ollie says his guesses out loud
🖍️ Crayon colours, Undo and Clear, works with mouse, touchscreen and stylus
🤔 Says "I don't know that one yet" instead of guessing wrong when unsure
🧠 How I built it
Dataset: ~1 million real doodles across 345 categories from Google's Quick, Draw! dataset
Model: a Convolutional Neural Network (CNN) I designed and trained myself in PyTorch: 3 convolution blocks and 2 dense layers, ~860K parameters
Runs in the browser: the trained model is exported to ONNX and runs with ONNX Runtime Web, so there's no server, no API, and drawings never leave the player's device
Preprocessing: each drawing is redrawn as a centred 28×28 image to match exactly what the model saw during training
Front end: HTML Canvas, CSS and JavaScript, with the browser's Web Speech API for Ollie's voice
🛠️ Tech stack
Python · PyTorch · ONNX · ONNX Runtime Web · JavaScript · HTML Canvas · CSS · Web Speech API · Netlify

📫 Contact
Source code is available on request.

Faiza Mehram, GitHub @faiza-mehram437


