# Lemmatization-of-Russian-Language-by-Tree-Regression-Models
Lemmatizer for Russian Language based on Tree Regression Models

Here, we train a set of tree based regressors on Russian language lemma-wordform wordpairs encoded by ordinal sequence. We compared our results with industry's MyStem (https://yandex.ru/dev/mystem/) and Pymorphy2 (https://pymorphy2.readthedocs.io/en/stable/) applications.

Russian dictionary source is http://odict.ru/.

The method is fully described in the article https://www.rcs.cic.ipn.mx/2020_149_3/An%20Open-Source%20Lemmatizer%20for%20Russian%20Language%20based%20on%20Tree%20Regression%20Models.pdf.

Working example of the lemmatizer in the form of web-app can be found at http://isa1.pythonanywhere.com/

It would be nice if you cite our article as:

@ARTICLE {akhmetoviskanderkrassovitskyalexanderualiyevairinagelbukhalexandermussabayevrustam2020,
    author  = "Akhmetov Iskander, Krassovitsky Alexander, Ualiyeva Irina , Gelbukh Alexander, Mussabayev Rustam",
    title   = "An Open-Source Lemmatizer for Russian Language based on Tree Regression Models",
    journal = "Research in Computing Science",
    year    = "2020",
    volume  = "149",
    number  = "3",
    pages   = "147-153",
    month   = "oct"
}
