# JupyShare
![alt text](https://image.ibb.co/ks7LEa/I9sa_R4ee_Q9qg8_IYRU_8_HIA.png)
![alt text](https://preview.ibb.co/fLbQfF/CJVTc_IBSRVWd_QEh_Aw_WMpjg.png)

JupyShare lets you release your notebook to the cloud and gives you a public endpoint for it through ngrok.
(Ngrok lets you expose localhost directly to the internet)

### Motivation
JupyShare is perfect for two things
1.  For freeing you up from the huge hassle of trying to debug jupyter notebooks with friends by taking screenshots or copy pasting.
2.  For showing something cool to a friend without having to tell them to download your masterpiece:

### Security
Ngrok provides a tunnel to your notebook so you definitely do not want to share the complete link (with the token and everything) with the world because any random person would pretty much have access to your own localhost and start running code on jupyter. To kill the connection to your notebook just run jupyshare kill or close your notebook.

### Prerequisites

The only thing necessary for JupyShare is ngrok.

```
brew cask install ngrok
```

### Installing

```
pip install jupyshare
```

### Commands

```
jupyshare release

jupyshare kill

jupyshare show

jupyshare --h or --help

jupyshare --browser BROWSER
```

## License

This project is licensed under the MIT License - see the [LICENSE.md](LICENSE.md) file for details



