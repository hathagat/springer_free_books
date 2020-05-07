## Another fork by Leo Barreiro from Springer Downloader, forked by hathagat

### Usage

Just run the script in the desired folder. It will automatically create a /download/ subfolder and will categorize the books acording the subject.

The books are organized in sub folders according to the categorize ("English Package Name" column).

Also download epub files if it's available.

### Usage in a virtual environment:

```bash
python3 -m venv .venv
. .venv/bin/activate
pip install -r requirements.txt
python3 main.py
```

### On Windows:

```
python -m venv .venv
cd .venv/Scripts
activate.bat
cd ../..
pip install -r requirements.txt
python main.py
```

### Source:
* https://group.springernature.com/gp/group/media/press-releases/freely-accessible-textbook-initiative-for-educators-and-students/17858180?utm_medium=social&utm_content=organic&utm_source=facebook&utm_campaign=SpringerNature_&sf232256230=1
* https://www.springernature.com/gp/librarians/news-events/all-news-articles/industry-news-initiatives/free-access-to-textbooks-for-institutions-affected-by-coronaviru/17855960
* https://resource-cms.springernature.com/springer-cms/rest/v1/content/17858272/data/v4

Thanks Springer!
