<!DOCTYPE html>
<html lang="en">

<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>
    phishing Detector
  </title>
  <link rel="icon" href="static/assets/favicon.ico">
  <link rel= "stylesheet" type= "text/css" href= "static/css/style.css">
  <link href="https://cdn.jsdelivr.net/npm/bootstrap@5.3.0-alpha3/dist/css/bootstrap.min.css" rel="stylesheet" integrity="sha384-KK94CHFLLe+nY2dmCWGMq91rCGa5gtU4mk92HdvYe+M/SXH301p5ILy+dN9+nJOZ" crossorigin="anonymous">
  <script src="https://kit.fontawesome.com/4e1316e6bd.js" crossorigin="anonymous"></script>
</head>

<body>
    <script src="https://code.jquery.com/jquery-3.2.1.slim.min.js" integrity="sha384-KJ3o2DKtIkvYIK3UENzmM7KCkRr/rE9/Qpg6aAZGJwFDMVNA/GpGFF93hXpG5KkN" crossorigin="anonymous"></script>
    <script src="https://cdn.jsdelivr.net/npm/popper.js@1.12.9/dist/umd/popper.min.js" integrity="sha384-ApNbgh9B+Y1QKtv3Rn7W3mgPxhU9K/ScQsAP7hUibX39j7fakFPskvXusvfa0b4Q" crossorigin="anonymous"></script>
    <script src="https://cdn.jsdelivr.net/npm/bootstrap@4.0.0/dist/js/bootstrap.min.js" integrity="sha384-JZR6Spejh4U02d8jOt6vLEHfe/JQGiRRSQQxSfFWpi1MquVdAyjUar5+76PVCmYl" crossorigin="anonymous"></script>

    <section id="navbar">
        <nav class="navbar navbar-expand-lg navbar-light" style="background-color: #F1F6F9;">
          <a class="navbar-brand" href="#">
            <img src="static/assets/AA.png" width="30" height="30" class="d-inline-block align-top" alt="">
            Assemble
          </a>
          <button class="navbar-toggler" type="button" data-toggle="collapse" data-target="#navbarSupportedContent" aria-controls="navbarSupportedContent" aria-expanded="false" aria-label="Toggle navigation">
            <span class="navbar-toggler-icon"></span>
          </button>

          <div class="collapse navbar-collapse" id="navbarSupportedContent">
            <ul class="navbar-nav ml-auto">
              <li class="nav-item">
                <a class="nav-link" href="#Home">Home</a>
              </li>
              <li class="nav-item">
                <a class="nav-link" href="#Model">Model</a>
              </li>
              <li class="nav-item">
                <a class="nav-link" href="#Contact">Contact</a>
              </li>

          </div>
        </nav>
      </section>


  <!-- Title -->
  <section id="Home" class="gradient-background">
    <div class="container col-xxl-8 px-4 py-5">
    <div class="row flex-lg-row-reverse align-items-center g-5 py-5">
      <div class="col-10 col-sm-8 col-lg-6">
        <img src="static/assets/goal images/phishing_img.png" class="d-block mx-lg-auto img-fluid" alt="Bootstrap Themes" width="700" height="500" loading="lazy">
      </div>
      <div class="col-lg-6">
        <h1 class="display-5 fw-bold lh-1 mb-3">What are phishing attacks?</h1>
        <p class="lead">Phishing attacks are fraudulent emails, text messages, phone calls or websites designed  to manipulate people into downloading malware,
          sharing sensitive information (e.g., Social Security and credit card numbers, bank account numbers,
          login credentials), or taking other actions that expose themselves or their organizations to cybercrime. To know more about phishing attack follow this link <a href="https://www.youtube.com/watch?v=XBkzBrXlle0">phishing</a>
        </p>
        
      </div>
    </div>
  </div>
  </section>


  <!-- Features -->
  <section id="Model">
    <div class="container col-xl-10 col-xxl-8 px-4 py-5">
    <div class="row align-items-center g-lg-5 py-5">
      <div class="col-lg-7 text-center text-lg-start">
        <h1 class="display-4 fw-bold lh-1 mb-3">Which one is a phishing site?</h1>
        <p class="col-lg-10 fs-4">To check that the URL you have got is safe or not, you can use our machine learning model to check whether the URL is safe or not.</p>
      </div>
      <div class="col-md-10 mx-auto col-lg-5">
        <form class="p-4 p-md-5 border rounded-3 bg-light" action="/#Model" method="post">
          <div class="form-floating mb-3">
            <input type="text" class="form-control" name="url" placeholder="www.hello.com">
            <label for="url">URL</label>
          </div>
          <div class="checkbox mb-3">
            <label>
              <input type="checkbox" value="remember-me"> Remember me
            </label>
          </div>
          <button class="w-100 btn btn-lg btn-primary" type="submit">Check</button>
          <hr class="my-4">
          <small class="text-muted">Check the URL by clicking</small>
        </form>
      </div>
    </div>
  </div>
  </section>



  <!-- Footer -->
  <section id="Contact" class="gradient-background">
    <footer class="pt-4 mt-md-5 pt-md-5 border-top">
    <div class="row">
      <div class="col-12 col-md">
        <img class="mb-2" src="static/assets/AA.png" alt="" width="24" height="19">
        <small class="d-block mb-3 text-muted">© kotla kiran</small>
      </div>
      <div class="col-6 col-md">
        <h5>Contact us</h5>
        <ul class="list-unstyled text-small">
          <li class="mb-1">
            <i class="fa-brands fa-instagram" style="color: #fcfcfc;"></i>
            <a class="link-secondary text-decoration-none" href="https://www.instagram.com/chimatashyam/">Instagram</a>
          </li>
          <li class="mb-1">
            <i class="fa-brands fa-linkedin" style="color: #fcfcfc;"></i>
            <a class="link-secondary text-decoration-none" href="https://www.linkedin.com/in/chimata-shyam-5b6077270/">linkedin</a>
          </li>
          <li class="mb-1">
            <i class="fa-brands fa-twitter" style="color: #fcfcfc;"></i>
            <a class="link-secondary text-decoration-none" href="https://twitter.com/chimatashyam123">Twitter</a></li>
        </ul>
      </div>
      <div class="col-6 col-md">
        <h5>Resources</h5>
        <ul class="list-unstyled text-small">
          <li class="mb-1"><i class="fa-solid fa-database" style="color: #fcfcfc;"></i>
            <a class="link-secondary text-decoration-none" href="#">Kaggle dataset</a>
          </li>
          <li class="mb-1"><i class="fa-brands fa-youtube" style="color: #fcfcfc;"></i>
            <a class="link-secondary text-decoration-none" href="#">Tarun tiwary</a>
          </li>
          <li class="mb-1"><i class="fa-brands fa-python" style="color: #fcfcfc;"></i>
            <a class="link-secondary text-decoration-none" href="#">Python ML</a>
          </li>
        </ul>
      </div>
      <div class="col-6 col-md">
        <h5>Our Team</h5>
        <ul class="list-unstyled text-small">
          <li class="mb-1"><a class="link-secondary text-decoration-none" href="#">Rajkumar</a></li>
          <li class="mb-1"><a class="link-secondary text-decoration-none" href="#">Kiran</a></li>
          <li class="mb-1"><a class="link-secondary text-decoration-none" href="#">Rashmitha</a></li>
          <li class="mb-1"><a class="link-secondary text-decoration-none" href="#">Harshitha</a></li>

        </ul>
      </div>
    </div>
  </footer>
  </section>
</body>

</html>


<!DOCTYPE html>
<html lang="en">
  <head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <meta http-equiv="X-UA-Compatible" content="ie=edge">
    <link rel= "stylesheet" type= "text/css" href= "static/css/style.css">
    <title>What site it is?</title><link href="https://cdn.jsdelivr.net/npm/bootstrap@5.3.0-alpha3/dist/css/bootstrap.min.css" rel="stylesheet" integrity="sha384-KK94CHFLLe+nY2dmCWGMq91rCGa5gtU4mk92HdvYe+M/SXH301p5ILy+dN9+nJOZ" crossorigin="anonymous">
    <script src="https://kit.fontawesome.com/4e1316e6bd.js" crossorigin="anonymous"></script>
  </head>
  <body>

  <section class="gradient-background">
       <div class="container col-xxl-8 px-4 py-5">
        <div class="row flex-lg-row-reverse align-items-center g-5 py-5">
          <div class="col-10 col-sm-8 col-lg-6">
            <img src="static/assets/safe.png" class="d-block mx-lg-auto img-fluid" alt="Bootstrap Themes" width="700" height="500" loading="lazy">
          </div>
          <div class="col-lg-6">
            <h1 class="display-5 fw-bold lh-1 mb-3">It is a safe and secured website</h1>
            <p class="lead">It is a safe and secured website, you proceed to it. If you want to know more details about this website
            or the redirect links of it, please contact us on kirankotla2002@gmail.com</p>
          </div>
        </div>
      </div>
  </section>

    <section id="Contact">
    <footer class="pt-4 mt-md-5 pt-md-5 border-top">
    <div class="row">
      <div class="col-12 col-md">
        <img class="mb-2" src="static/assets/AA.png" alt="" width="24" height="19">
        <small class="d-block mb-3 text-muted">© Raj Kumar</small>
      </div>
      <div class="col-6 col-md">
        <h5>Contact us</h5>
        <ul class="list-unstyled text-small">
          <li class="mb-1">
            <i class="fa-brands fa-instagram" style="color: #fcfcfc;"></i>
            <a class="link-secondary text-decoration-none" href="https://www.instagram.com/chimatashyam/">Instagram</a>
          </li>
          <li class="mb-1">
            <i class="fa-brands fa-linkedin" style="color: #fcfcfc;"></i>
            <a class="link-secondary text-decoration-none" href="https://www.linkedin.com/in/chimata-shyam-5b6077270/">linkedin</a>
          </li>
          <li class="mb-1">
            <i class="fa-brands fa-twitter" style="color: #fcfcfc;"></i>
            <a class="link-secondary text-decoration-none" href="https://twitter.com/chimatashyam123">Twitter</a></li>
        </ul>
      </div>
      <div class="col-6 col-md">
        <h5>Resources</h5>
        <ul class="list-unstyled text-small">
          <li class="mb-1"><i class="fa-solid fa-database" style="color: #fcfcfc;"></i>
            <a class="link-secondary text-decoration-none" href="#">Kaggle dataset</a>
          </li>
          <li class="mb-1"><i class="fa-brands fa-youtube" style="color: #fcfcfc;"></i>
            <a class="link-secondary text-decoration-none" href="#">Tarun tiwary</a>
          </li>
          <li class="mb-1"><i class="fa-brands fa-python" style="color: #fcfcfc;"></i>
            <a class="link-secondary text-decoration-none" href="#">Python ML</a>
          </li>
        </ul>
      </div>
      <div class="col-6 col-md">
        <h5>Our Team</h5>
        <ul class="list-unstyled text-small">
          <li class="mb-1"><a class="link-secondary text-decoration-none" href="#">Rajkumar</a></li>
          <li class="mb-1"><a class="link-secondary text-decoration-none" href="#">Kiran</a></li>
          <li class="mb-1"><a class="link-secondary text-decoration-none" href="#">Rashmitha</a></li>
          <li class="mb-1"><a class="link-secondary text-decoration-none" href="#">Harshitha</a></li>

        </ul>
      </div>
    </div>
  </footer>
  </section>

  </body>
</html>



<!DOCTYPE html>
<html lang="en">
  <head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <meta http-equiv="X-UA-Compatible" content="ie=edge">
    <link rel= "stylesheet" type= "text/css" href= "static/css/style.css">
    <title>What site it is?</title><link href="https://cdn.jsdelivr.net/npm/bootstrap@5.3.0-alpha3/dist/css/bootstrap.min.css" rel="stylesheet" integrity="sha384-KK94CHFLLe+nY2dmCWGMq91rCGa5gtU4mk92HdvYe+M/SXH301p5ILy+dN9+nJOZ" crossorigin="anonymous">
    <script src="https://kit.fontawesome.com/4e1316e6bd.js" crossorigin="anonymous"></script>
  </head>
  <body>

  <section class="gradient-background">
       <div class="container col-xxl-8 px-4 py-5">
        <div class="row flex-lg-row-reverse align-items-center g-5 py-5">
          <div class="col-10 col-sm-8 col-lg-6">
            <img src="static/assets/bad.jpeg" class="d-block mx-lg-auto img-fluid" alt="Bootstrap Themes" width="700" height="500" loading="lazy">
          </div>
          <div class="col-lg-6">
            <h1 class="display-5 fw-bold lh-1 mb-3">It is not safe to browse</h1>
            <p class="lead">It is not a safe website, please avoid it. if you still want to browse through it go a head but, remember that you are not safe here.
                If you want to know more details about this website
            or the redirect links of it, please contact us on chimatashyam123@gmail.com</p>
          </div>
        </div>
      </div>
  </section>

    <section id="Contact">
    <footer class="pt-4 mt-md-5 pt-md-5 border-top">
    <div class="row">
      <div class="col-12 col-md">
        <img class="mb-2" src="static/assets/AA.png" alt="" width="24" height="19">
        <small class="d-block mb-3 text-muted">© chimata shyam</small>
      </div>
      <div class="col-6 col-md">
        <h5>Contact us</h5>
        <ul class="list-unstyled text-small">
          <li class="mb-1">
            <i class="fa-brands fa-instagram" style="color: #fcfcfc;"></i>
            <a class="link-secondary text-decoration-none" href="https://www.instagram.com/chimatashyam/">Instagram</a>
          </li>
          <li class="mb-1">
            <i class="fa-brands fa-linkedin" style="color: #fcfcfc;"></i>
            <a class="link-secondary text-decoration-none" href="https://www.linkedin.com/in/chimata-shyam-5b6077270/">linkedin</a>
          </li>
          <li class="mb-1">
            <i class="fa-brands fa-twitter" style="color: #fcfcfc;"></i>
            <a class="link-secondary text-decoration-none" href="https://twitter.com/chimatashyam123">Twitter</a></li>
        </ul>
      </div>
      <div class="col-6 col-md">
        <h5>Resources</h5>
        <ul class="list-unstyled text-small">
          <li class="mb-1"><i class="fa-solid fa-database" style="color: #fcfcfc;"></i>
            <a class="link-secondary text-decoration-none" href="#">Kaggle dataset</a>
          </li>
          <li class="mb-1"><i class="fa-brands fa-youtube" style="color: #fcfcfc;"></i>
            <a class="link-secondary text-decoration-none" href="#">Tarun tiwary</a>
          </li>
          <li class="mb-1"><i class="fa-brands fa-python" style="color: #fcfcfc;"></i>
            <a class="link-secondary text-decoration-none" href="#">Python ML</a>
          </li>
        </ul>
      </div>
      <div class="col-6 col-md">
        <h5>Our Team</h5>
        <ul class="list-unstyled text-small">
          <li class="mb-1"><a class="link-secondary text-decoration-none" href="#">Shyam</a></li>
          <li class="mb-1"><a class="link-secondary text-decoration-none" href="#">Rupendra</a></li>
          <li class="mb-1"><a class="link-secondary text-decoration-none" href="#">Ramesh</a></li>
          <li class="mb-1"><a class="link-secondary text-decoration-none" href="#">Yashwanth</a></li>

        </ul>
      </div>
    </div>
  </footer>
  </section>

  </body>
</html>



# importing the modules
import pandas as pd # use for data manipulations and analysis
import numpy as np # use for multi-dimensional array and matrix
import matplotlib.pyplot as plt # provides object oriented API
import seaborn as sns # use for high-level interface for drawing attractive and statistical graphics
# %matplotlib inline
from sklearn.linear_model import LogisticRegression # algo use to predict good or bad
from sklearn.naive_bayes import MultinomialNB # natural language processing(nlp) algo use to predict good or bad
from sklearn.model_selection import train_test_split
from sklearn.metrics import classification_report
from sklearn.metrics import confusion_matrix
from nltk.tokenize import RegexpTokenizer # regression expression tokenizers use to split words from text
from nltk.stem.snowball import SnowballStemmer
from sklearn.feature_extraction.text import CountVectorizer
from sklearn.pipeline import make_pipeline
import time  # calculate time
from PIL import Image
from wordcloud import WordCloud, STOPWORDS, ImageColorGenerator # creates words cloud
from bs4 import BeautifulSoup
from selenium import webdriver
import networkx as nx
import pickle
import warnings   # ignores
warnings.filterwarnings('ignore')


def plot_wordcloud(text, mask=None, max_words=400, max_font_size=120, figure_size=(24.0, 16.0),
                   title=None, title_size=40, image_color=False):
    stopwords = set(STOPWORDS)
    more_stopwords = {'com', 'http'}
    stopwords = stopwords.union(more_stopwords)

    wordcloud = WordCloud(background_color='white',
                          stopwords=stopwords,
                          max_words=max_words,
                          max_font_size=max_font_size,
                          random_state=42,
                          mask=mask)
    wordcloud.generate(text)

    plt.figure(figsize=figure_size)
    if image_color:
        image_colors = ImageColorGenerator(mask);
        plt.imshow(wordcloud.recolor(color_func=image_colors), interpolation="bilinear");
        plt.title(title, fontdict={'size': title_size,
                                   'verticalalignment': 'bottom'})
    else:
        plt.imshow(wordcloud);
        plt.title(title, fontdict={'size': title_size, 'color': 'green',
                                   'verticalalignment': 'bottom'})
    plt.axis('off');
    plt.tight_layout()


data = pd.read_csv("phishing_site_urls.csv")
data.columns = ['URL', 'Label']
label_counts = pd.DataFrame(data.Label.value_counts())
tokenizer = RegexpTokenizer(r'[A-Za-z]+')
tokenizer.tokenize(data.URL[0])

print('Getting words tokenized ...')
t0 = time.perf_counter()
data['text_tokenized'] = data.URL.map(lambda t: tokenizer.tokenize(t))
t1 = time.perf_counter() - t0
print('Time taken', t1, 'sec')

stemmer = SnowballStemmer("english")
print('Getting words stemmed ...')
t0 = time.perf_counter()
data['text_stemmed'] = data['text_tokenized'].map(lambda l: [stemmer.stem(word) for word in l])
t1 = time.perf_counter() - t0
print('Time taken', t1, 'sec')

print('Getting joiningwords ...')
t0 = time.perf_counter()
data['text_sent'] = data['text_stemmed'].map(lambda l: ' '.join(l))
t1 = time.perf_counter() - t0
print('Time taken', t1, 'sec')

print(data.text_sent)


bad_sites = data[data.Label == 'bad']
good_sites = data[data.Label == 'good']

data1 = good_sites.text_sent
data1.reset_index(drop=True, inplace=True)
common_text = str(data1)
# common_mask = np.array(Image.open('star.png'))
plot_wordcloud(common_text, max_words=400, max_font_size=120,
               title = 'Most common words use in good urls', title_size=15)
data = bad_sites.text_sent
data.reset_index(drop=True, inplace=True)
common_text = str(data1)
# common_mask = np.array(Image.open('comment.png'))
plot_wordcloud(common_text, max_words=400, max_font_size=120,
               title = 'Most common words use in bad urls', title_size=15)


data = pd.read_csv("phishing_site_urls.csv")
print(data.head())
data.columns = ['URL', 'Label']
label_counts = pd.DataFrame(data.Label.value_counts())
tokenizer = RegexpTokenizer(r'[A-Za-z]+')
tokenizer.tokenize(data.URL[0])

print('Getting words tokenized ...')
t0 = time.perf_counter()
data['text_tokenized'] = data.URL.map(lambda t: tokenizer.tokenize(t))
t1 = time.perf_counter() - t0
print('Time taken', t1, 'sec')

stemmer = SnowballStemmer("english")
print('Getting words stemmed ...')
t0 = time.perf_counter()
data['text_stemmed'] = data['text_tokenized'].map(lambda l: [stemmer.stem(word) for word in l])
t1 = time.perf_counter() - t0
print('Time taken', t1, 'sec')

print('Getting joiningwords ...')
t0 = time.perf_counter()
data['text_sent'] = data['text_stemmed'].map(lambda l: ' '.join(l))
t1 = time.perf_counter() - t0
print('Time taken', t1, 'sec')

cv = CountVectorizer()
feature = cv.fit_transform(data.text_sent)
feature[:5].toarray()
trainX, testX, trainY, testY = train_test_split(feature, data.Label)
lr = LogisticRegression()
lr.fit(trainX, trainY)
lr.score(testX, testY)
Scores_ml = {}
Scores_ml['Logistic Regression'] = np.round(lr.score(testX,testY),2)
print('Training Accuracy :',lr.score(trainX,trainY))
print('Testing Accuracy :',lr.score(testX,testY))
con_mat = pd.DataFrame(confusion_matrix(lr.predict(testX), testY),
            columns = ['Predicted:Bad', 'Predicted:Good'],
            index = ['Actual:Bad', 'Actual:Good'])


print('\nCLASSIFICATION REPORT\n')
print(classification_report(lr.predict(testX), testY,
                            target_names =['Bad','Good']))

print('\nCONFUSION MATRIX')
plt.figure(figsize= (6,4))
sns.heatmap(con_mat, annot = True,fmt='d',cmap="YlGnBu")

mnb = MultinomialNB()
mnb.fit(trainX,trainY)
mnb.score(testX,testY)
Scores_ml['MultinomialNB'] = np.round(mnb.score(testX,testY),2)
print('Training Accuracy :',mnb.score(trainX,trainY))
print('Testing Accuracy :',mnb.score(testX,testY))
con_mat = pd.DataFrame(confusion_matrix(mnb.predict(testX), testY),
            columns = ['Predicted:Bad', 'Predicted:Good'],
            index = ['Actual:Bad', 'Actual:Good'])


print('\nCLASSIFICATION REPORT\n')
print(classification_report(mnb.predict(testX), testY,
                            target_names =['Bad','Good']))

print('\nCONFUSION MATRIX')
plt.figure(figsize= (6,4))
sns.heatmap(con_mat, annot = True,fmt='d',cmap="YlGnBu")
acc = pd.DataFrame.from_dict(Scores_ml,orient = 'index',columns=['Accuracy'])
sns.set_style('darkgrid')
plt.bar(acc.index,acc.Accuracy, color=['orange', 'yellow'], width=0.6)
pipeline_ls = make_pipeline(CountVectorizer(tokenizer = RegexpTokenizer(r'[A-Za-z]+').tokenize,stop_words='english'), LogisticRegression())
trainX, testX, trainY, testY = train_test_split(data.URL, data.Label)
pipeline_ls.fit(trainX,trainY)
pipeline_ls.score(testX,testY)
print('Training Accuracy :',pipeline_ls.score(trainX,trainY))
print('Testing Accuracy :',pipeline_ls.score(testX,testY))
con_mat = pd.DataFrame(confusion_matrix(pipeline_ls.predict(testX), testY),
            columns = ['Predicted:Bad', 'Predicted:Good'],
            index = ['Actual:Bad', 'Actual:Good'])


print('\nCLASSIFICATION REPORT\n')
print(classification_report(pipeline_ls.predict(testX), testY,
                            target_names =['Bad','Good']))

print('\nCONFUSION MATRIX')
plt.figure(figsize= (6,4))
sns.heatmap(con_mat, annot = True,fmt='d',cmap="YlGnBu")
pickle.dump(pipeline_ls,open('phishing.pkl','wb'))
loaded_model = pickle.load(open('phishing.pkl', 'rb'))
result = loaded_model.score(testX,testY)
print(result)
loaded_model = pickle.load(open('phishing.pkl', 'rb'))
result1 = loaded_model.predict(['yeniik.com.tr/wp-admin/js/login.alibaba.com/login.jsp.php'])
result2 = loaded_model.predict(['youtube.com/'])
print(result1)
print("*"*30)
print(result2)

