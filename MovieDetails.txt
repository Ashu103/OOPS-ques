class MovieDetails:
    def __init__(self,mname,aname,yrel,rating):
        self.mname=mname
        self.aname=aname
        self.yrel=yrel
        self.rating=rating
    def Display(self):
        print('MovieName: {}, ArtistName: {}, YaarofRelease: {},Rating: {}'.format(self.mname,self.aname,self.yrel,self.rating))


m1=MovieDetails('TheDarkKnight','ChristianBale',2008,9)
m2=MovieDetails('Race3','Salman khan',2018,'these type of movies does not need ratings they only need blind fan following')
m1.Display()
m2.Display()