# My Favorite Artists: Spotify Exploratory Data Analysis
## by Harsh Deep Kalita
## Introduction
>One of the apps I have used extensively is the Spotify app for listening to music. In this project, I used the spotipy library, a Python library for the Spotify Web API. It was a really helpful library for extracting data from my desired/favourite artists. I have mentioned all the data-cleaning steps in my project.I performed Univariate, Bivariate, and Multivariate Analysis to investigate my created dataset, this is called the Exploratory Data Analysis Part.At the end comes the Explanatory Data Analysis Part where I displayed all my insights in a simplified format so that the viewers can understand the insights easily.  
There are 3 parts to my project:
      1. Preliminary Wrangling
      2. Exploratory Data Analysis
      3. Explanatory Data Analysis

<b>Note</b>: the the exploratory analysis is based on the artists mentioned in my list: 'Ed Sheeran','Shawn Mendes','Calvin Harris','Justin Bieber','Charlie Puth','Martin Garrix',
'The Chainsmokers','Alan Walker','Dua Lipa','Bruno Mars','AC/DC','Kanye West',"Guns N' Roses",'Green Day','The Weeknd','Eminem','Bob Marley'.



## Summary and Conclusions

<p>
      
### 1) Energy and Loudness / Danceability and Valence :- <br>

- Majority of songs are <b>more in energy as well as loudness</b>.
- The majority songs have <b>loudness between -7.5 to -3.5 and the popularity range is from 45 to 75.</b> There are still some outliers present.
- Higher <b>dancable songs have higher valence</b>(more positive/happy feeling).
- <b>Bob Marley & The Willers have given the highest positive feeling songs</b> to the listeners, then comes which is an American Rock Band. Dua Lipa, Calvin Harris, Bruno Mars, and Charlie Puth have almost the same valence value.
- <b>Bob Marley and The Wallers have released quite danceable songs</b>. All the rock bands have the lowest danceability

### 2) Liveness :-<br>

- Majority of the songs are <b>less in liveness (0.05 to 0.2.) and more in energy</b>.
- Liveness is overall less in majority of songs, as our songs are more from album covers than live covers hence this was expected.
- The rapper artists and rock bands have high liveness in their songs compared to the pop artists.<b>ACDC has the highest liveness, then comes Eminem and Kanye (both are rappers).</b>

### 3) Popularity :-<br>

- The majority of songs fall in the range of 45 to 70.
- <b>"Doo-Wops & Hooligans" album by Bruno Mars has the highest popularity of 77</b>, second, comes "My Beautiful Dark Twisted Fantasy" by Kanye West and the third highest popular album is "Graduation" by Kanye West.
- <b>Kanye West and The Weeknd have the highest number of popular albums</b>, Second is Bruno Mars, and Third are Eminem and ED Sheeran, they have the same number of highly popular albums.
- The <b>most famous song is "Mocking Bird" by Eminem!! The popularity is 88</b> for this song.
- <b>Kanye West is the highest popular artist</b>, and Eminem/Weeknd/Dua Lipa are almost the same in popularity.

### 4) Album_type :-<br>

- That the <b>albumtype 'Album' has the highest count</b>. Then comes Singles,Deluxe and Compilation.
- <b>Interestingly the songs of "Single" album type are more popular than the songs of the "Album" album type</b>, but we also have to consider the error bars of these data points, the "Album" album_type data is concentrated and is signaling that the plotted average is more likely/reliable, compared to the "Single" album_type data. Album and Deluxe albums are almost equal in popularity. The compilation album has the lowest popularity.
- <b>The songs from a Deluxe album do give a positive boost to the popularity of a song if that song is near the 80 to 100 range popularity</b>, otherwise, the original album songs are higher in popularity than the Deluxe Album songs.


### 5) Releases_date, Year, Month :-<br>

- <b>According to per year we can observe an increasing trend of releases of songs</b>, as we have just started with the year 2023, we do not have many releases yet from the artists that I have chosen for my analysis. The <b>months when the highest number of songs have been released are October, November, June, April, and January.</b>
- The <b>months when the popularity is at its peak in Feb and Sept.</b>
- The <b>popularity per year</b> has been fluctuating a lot and is not consistent (<b>no particular trend</b>). The popularity started at 55 in the year 1973, there was a sudden decrease in the popularity at the start of the year 1990 but it recovered in the mid of the 1990s, after that the popularity started increasing gradually.

### 6) Key and Mode :-<br>

- For the key variable, <b>High number of songs were made in the key 1-2 (Csharp and D scale)</b>, moderate number of songs used the key 4 to 11 and 1 (E to B scale and C scale), key 3 (D#/Eflat scale) was used the least.
- Key 3 has the highest popularity but this key has been used the lowest number of times by the artists. <b>The safest Key Signature to use for making a popular song looks like the Key 0 and Key 8.</b>
- Songs in <b>Mode 0 have higher popularity than Mode 1 </b>but, the number of songs in Mode 1 is more than the number of songs in Mode 0.The reason could be that at the high end of the popularity scale (77 to 81) Mode 0's frequency is higher than Mode 1's.

### 7) Duration_m :-<br>

- The majority of songs have the <b>duration between 3 to 4.5 minutes.</b> 
- The low end outliers are either interlude or intro songs and the highest duration song(12.08 minutes long) is "Last Call" by Kanye West.

### 8) Tempo and Tempo_type :- <br>

- Artists have <b>used fast tempo more than moderate and slow</b>. Although, moderate and fast tempo do not have a huge gap. The least used tempo was "slow".

### 9) Time signature :-<br>

- <b>Time signature 4 has been extensively used by the artists</b>. Which is not shocking as 4/4 is the most commonly used time signature. The gap between the 4 and rest of the time signatures is significantly high.

</p>
