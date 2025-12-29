## Chess Position Advantage Prediction Using CNN and Image Processing

### Summary
- **Developed a CNN-based model** achieving **69.43% hidden test accuracy** and **68.76% validation accuracy** for predicting chess position advantages (Black, White, Equal).
- **Processed 22,000+ labeled chessboard positions**, incorporating image features (**SSIM, Canny Edge Detector**) and chess-specific metrics such as **center control, piece safety, clustering, mobility, pawn structure, and king safety**.
- **Optimized model performance** through hyperparameter tuning (32-256 filters, dropout rates 0.2-0.3, learning rate 0.001).
- **Implemented feature extraction and deep learning workflows** using TensorFlow and Python.

### Technologies Used
- **Programming Languages:** Python  
- **Deep Learning Frameworks:** TensorFlow, Keras  
- **Image Processing Tools:** SSIM, Canny Edge Detector, OpenCV  
- **Libraries:** NumPy, Pandas, Scikit-learn  
- **Optimization Techniques:** Hyperparameter Tuning


<img width="1430" alt="1" src="https://github.com/user-attachments/assets/04bfed85-d295-4c14-9a5a-c0231c390fcd">
<img width="1430" alt="2" src="https://github.com/user-attachments/assets/2a3d5e7a-b210-4865-ab55-1736f5dfa2e3">
<img width="1430" alt="3" src="https://github.com/user-attachments/assets/383c7f1e-00fb-4dd8-8801-cb6c9d8cfe9d">
<img width="1430" alt="4" src="https://github.com/user-attachments/assets/3f6c8e16-4669-4422-b408-ba173873d1d7">
<img width="1430" alt="5" src="https://github.com/user-attachments/assets/de1653f2-032a-44ff-9b0c-2c49ad057ef2">
<img width="1430" alt="6" src="https://github.com/user-attachments/assets/1c299fd8-eb65-4928-9af7-03567a0a18d0">
<img width="1430" alt="7" src="https://github.com/user-attachments/assets/cd2a8d44-d035-4224-a26d-3cb92c390e50">
<img width="1430" alt="8" src="https://github.com/user-attachments/assets/f065c0ca-92f4-42ea-af10-553f464c6374">
<img width="1430" alt="9" src="https://github.com/user-attachments/assets/f29f0189-a53a-498f-a95b-d24c9069a823">
<img width="1430" alt="10" src="https://github.com/user-attachments/assets/47da41eb-7c62-4a3c-8a71-fbb2a8ecfe30">
<img width="1430" alt="11" src="https://github.com/user-attachments/assets/ff3aab5a-306c-4342-b7de-23f2dcd297c0">
The 2D-projection part is heavily based on https://arxiv.org/pdf/1708.03898.pdf and the related project: https://github.com/maciejczyzewski/neural-chessboard
Collecting data: https://tech.bakkenbaeck.com/post/chessvision#chessboard-recognition
CNN architecture: https://towardsdatascience.com/a-single-function-to-streamline-image-classification-with-keras-bd04f5cfe6df
https://par.nsf.gov/servlets/purl/10099572
https://towardsdatascience.com/board-game-image-recognition-using-neural-networks-116fc876dafa
https://web.stanford.edu/class/cs231a/prev_projects_2016/CS_231A_Final_Report.pdf
https://cvgl.stanford.edu/teaching/cs231a_winter1415/prev/projects/chess.pdf
https://github.com/bakkenbaeck/chessboardeditor
https://github.com/jialinding/ChessVision
https://machinelearningmastery.com/how-to-implement-major-architecture-innovations-for-convolutional-neural-networks/
https://stackoverflow.com/questions/56754543/generate-chess-board-diagram-from-an-array-of-positions-in-python
https://www.programcreek.com/python/?code=yaqwsx%2FPcbDraw%2FPcbDraw-master%2Fpcbdraw%2Fpcbdraw.py#
https://chess.stackexchange.com/questions/28870/render-a-chessboard-from-a-pgn-file
