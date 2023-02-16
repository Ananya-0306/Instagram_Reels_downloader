# Instagram Reels Downloader
![Instagram Reels Downloader](https://github.com/Ananya-0306/Instagram_Reels_downloader/blob/main/reels%20(1).png)

You all are now aware that there is a number of python libraries to get creative and solve some real-life problems with code! Do you hear about libraries like Insta Bot, instaloader, instascrape?? As their name seems, they provide Instagram API.

You can download profile pic, posts, igtv’s, highlights, stories and keep track of comments, views, likes not only of your favorite celebrity i.e. people with public accounts but also private accounts!
These libraries provide you the facility to do so!
Here, let’s save reels from Instagram as they cannot be saved over the app itself, we can actually download them!
Here, we will download reels of public accounts. You can download of privately but it would require the user id and password of your insta account.
Here, let’s save reels from Instagram as they cannot be saved over the app itself, we can actually download them!</br>

## Development Tutorial

Follow the steps : https://develover.hashnode.dev/download-instagram-reels-using-python

## Installation

Use the package manager [pip](https://pip.pypa.io/en/stable/) to install Instagram Reels Downloader.

```bash
pip install instascrape
```

## Usage

Download the repository locally, then we need to pass the session id into the headers as follows: <br>
**Note**: SessionID changes every time when you log out. Make sure that you provide the id at the time when you are logged in.

```python
SESSIONID = "{your session id}"
            headers = {
            "User-Agent": "Mozilla/5.0 (Windows NT 10.0; Win64; x64) AppleWebKit/537.36 (KHTML, like Gecko) Chrome/79.0.3945.74 Safari/537.36 Edg/79.0.309.43",
            "cookie":f'sessionid={SESSIONID};'
            }
google_reel.scrape(headers=headers)
```

Now, open the terminal by searching for it in the dashboard or pressing Ctrl + Alt + T . Navigate the terminal to the directory where the project is located using the cd command. Type 

```python
python instareels/reels.py
```
in the terminal to execute the script.

## Contributing

Pull requests are welcome. For major changes, please open an issue first
to discuss what you would like to change.

Please make sure to update tests as appropriate.

## License

[GNU General Public License v3.0](https://github.com/Ananya-0306/Instagram_Reels_downloader/blob/main/LICENSE)
