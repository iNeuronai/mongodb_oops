
import pymongo
client = pymongo.MongoClient("mongodb+srv://mongodb:mongodb@cluster0.qivyyos.mongodb.net/?retryWrites=true&w=majority")
db = client.test


db = client['ineuron']
col = db['course']
col1 = db['studets']

data = {
    'course_name' : ['full stack data science ','full stack data analytics' , 'big data' , 'devops' , 'blockchain'],
    'course_instructor' : ['sudhanshu' ,'anand' , 'shashank' , 'hitesh' , 'navin'],
    'start_date' : '12-12-2023',
    'duration' : 'six months',
    'mode' : 'live online',
    'certification' : 'yes',
    'prequisite' : ' Dedication',
    'resume' : 'yes',
    'mockinterview' : 'yes'
    
}


col.insert_one(data)



data1 = {
    'name' : 'full stack web dev' ,
    'instructor' : ['hitesh' , 'anurag'],
    'price ' : '17700',
    'duration' : 'eight month' 
    
}


col.delete_many({'duration': 'six months'})


col.update_many({"price ":'1800'} , {"$set" : {"price " : 18000}})



col.insert_one(data1)


rec = col.find()

from pprint import pprint
for i in rec :
    pprint(i)
    
    
    
    
 class and objects : 
 
 
 class ineuron : 
    
    def ineuron1(self):
        print("ineuron is a compnay in edtech")
        
    def ineron_students(self):
        print("students are amazing in ineuron")
        
    def ineuron_support(self):
        print("yes we do give support")
    
    def ineuron_fee(self):
        print("its very very affordable ") 
        
        
        
        
import pymongo
class mongodb : 
    
    def __init__(self , userid1 , password1, data ) :
        
        """
        this is a code for mongodb connectivity and its related application 
        """
        self.userid = userid1
        self.password = password1 
        self.data = data 
    
    
    def connect(self) :
        print("this fun will help you to coonnect with your mongo db ")
        url = "mongodb+srv://" + self.userid + ":" + self.password+ "@cluster0.qivyyos.mongodb.net/?retryWrites=true&w=majority"
        client = pymongo.MongoClient(url)
        return client
        
    def insert(self ):
        conn = self.connect()
        print("this fun will help you to insert into mondo db ")
        db = conn['mongodb_test']
        coll = db['mongo_record']
        coll.insert_one(self.data)
        
    def update(self):
        print("this fun will help you to update in mongodb")
