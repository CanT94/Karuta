<!DOCTYPE html>
<html>
<head>
<title>Karuta Card Game by Can Tosun</title>
<meta charset="utf-8">
<meta name = "viewport" content = "width=device-width, initial-scale = 1">
<link rel="preconnect" href="https://fonts.googleapis.com">
<link rel="preconnect" href="https://fonts.gstatic.com" crossorigin>
<link href="https://fonts.googleapis.com/css2?family=Roboto&display=swap" rel="stylesheet">
<link href="https://fonts.googleapis.com/icon?family=Material+Icons" rel="stylesheet">
</head>

<body>
    <div id="headerDiv">
        <h1>
            Karuta Card Game
        </h1>
        <h2>
            English Pop Edition
        </h2>
        <h3>
            by Can Tosun
        </h3>
    </div>
    <br/>
    <br/>
    <p >Artist:</p>
    <p id="currentSongArtist"></p>
    <p >Title:</p>
    <p id="currentSongTitle"></p>
    <br/>
    <br/>
    <br/>
    <p id="statusText"></p>
    <button onclick="PlaySong()">
        <span class="material-icons" id="playPauseIcon">play_arrow</span>
        <span id="playPauseSpan">Play Song</span>
    </button>
    <button onclick="RevealSong()">
        <span class="material-icons" id="revealIcon">visibility</span>
        <span id="revealSpan">Reveal Song</span>
    </button>
    <button onclick="NextSong()">
        <span class="material-icons">fast_forward</span>
        <span>Next Song</span>
    </button>
    <script>
        let songList = [{artist: "Ed Sheeran", title: "Shape of You", lyrics: "The club isn't the best place to find a lover. So the bar is where I go. Me and my friends at the table doing shots. Drinking fast and then we talk slow. And you come over and start up a conversation with just me. And trust me I'll give it a chance now. Take my hand, stop, put Van the Man on the jukebox. And then we start to dance, and now I'm singing like"},
                        {artist: "Akon", title: "Lonely", lyrics: "I woke up in the middle of the night. And I noticed my girl wasn't by my side. Coulda sworn I was dreaming, for her I was feenin'. So I had to take a little ride. Back tracking over these few years. Tryna figure out what I do to make it go bad. 'Cause ever since my girl left me. My whole life came crashing and I'm so"},
                        {artist: "Wiz Khalifa, Snoop Dogg", title: "Young, Wild & Free", lyrics: "Is this thing on? (word). So what we get drunk. So what we smoke weed. We're just having fun. We don't care who sees (shit). So what we go out. That's how its supposed to be. Living young and wild and free"},
                        {artist: "The Weeknd", title: "Party Monster", lyrics: "And I've seen her get richer in the pole. I've seen her, I knew she had to know. I've seen her take down that tequila. Down by the liter, I knew I had to meet her. Ooh, she mine, ooh, girl, bump and grind. Ooh, she mine, ooh, girl, bump a line. Angelina, lips like Angelina. Like Selena, ass shaped like Selena"},
                        {artist: "Drake", title: "Hotline Bling", lyrics: "Ever since I left the city, you. Got a reputation for yourself now. Everybody knows and I feel left out. Girl you got me down, you got me stressed out. Cause ever since I left the city, you. Started wearing less and goin' out more. Glasses of champagne out on the dance floor. Hangin' with some girls I've never seen before"},
                        {artist: "Drake", title: "One Dance", lyrics: "Strength and guidance. All that I'm wishing for my friends. Nobody makes it from my ends. I had to bust up the silence. You know you gotta stick by me. Soon as you see the text, reply me. I don't wanna spend time fighting. We've got no time"},
                        {artist: "Post Malone", title: "Rockstar", lyrics: "Ayy, ayy, switch my whip, came back in black. I'm startin' sayin', Rest in peace to Bon Scott. Ayy, close that door, we blowin' smoke. She ask me light a fire like I'm Morrison. Ayy, act a fool on stage. Prolly leave my fuckin' show in a cop car. Ayy, shit was legendary. Threw a TV out the window of the Montage. Cocaine on the table, liquor pourin', don't give a damn. Dude, your girlfriend is a groupie, she just tryna get in. Sayin', I'm with the band. Ayy, ayy, now she actin' outta pocket. Tryna grab up from my pants. Hundred bitches in my trailer say they ain't got a man. And they all brought a friend. Yeah, ayy"},
                        {artist: "The Weeknd, Daft Punk", title: "Starboy", lyrics: "House so empty, need a centerpiece. 20 racks a table cut from ebony. Cut that ivory into skinny pieces. Then she clean it with her face man I love my baby. You talking money, need a hearing aid. You talking bout me, I don't see the shade. Switch up my style, I take any lane. I switch up my cup, I kill any pain"},
                        {artist: "The Weeknd", title: "False Alarm", lyrics: "She loves everybody. Can't you tell by the signs?. She loves everybody. She gets off all the time. It's a dark philosophy. And it haunts her constantly. It's a false alarm to me. She's a false alarm"},
                        {artist: "Desiigner", title: "Panda", lyrics: "I got broads in Atlanta. Twistin' dope, lean, and the Fanta. Credit cards and the scammers. Hittin' off licks in the bando. Black X6, Phantom. White X6 looks like a panda. Goin' out like I'm Montana. Hundred killers, hundred hammers. Black X6, Phantom. White X6, panda"},
                        {artist: "The Cranberries", title: "Zombie", lyrics: "Another head hangs lowly. Child is slowly taken. And the violence caused such silence. Who are we mistaken?. But you see, it's not me. It's not my family. In your head, in your head, they are fighting. With their tanks, and their bombs. And their bombs, and their guns. In your head, in your head they are crying"},
                        {artist: "Lady Gaga", title: "Just Dance", lyrics: "I've had a little bit too much, much (Oh, oh, oh-oh). All of the people start to rush (Start to rush by). A dizzy twister dance. Can't find my drink or man. Where are my keys?. I lost my phone, phone (Oh, oh, oh-oh). What's going on on the floor?. I love this record, baby, but I can't see straight anymore. Keep it cool. What's the name of this club?. I can't remember, but it's alright, alright"},
                        {artist: "Adele", title: "Rolling in the Deep", lyrics: "There's a fire starting in my heart. Reaching a fever pitch and it's bringin' me out the dark. Finally I can see you crystal clear. Go ahead and sell me out and I'll lay your shit bare. See how I'll leave with every piece of you. Don't underestimate the things that I will do. There's a fire starting in my heart. Reaching a fever pitch and it's bringin' me out the dark"},
                        {artist: "Justin Bieber", title: "Baby", lyrics: "You know you love me, I know you care. Just shout whenever, and I'll be there. You are my love, you are my heart. And we will never, ever, ever be apart. Are we an item? Girl, quit playin'. We're just friends, what are you sayin'?. Said there's another, and looked right in my eyes. My first love broke my heart for the first time"},
                        {artist: "Rihanna", title: "Umbrella", lyrics: "You have my heart. And we'll never be worlds apart. Maybe in magazines. But you'll still be my star. Baby, 'cause in the dark. You can't see shiny cars. And that's when you need me there. With you, I'll always share. Because. When the sun shine, we shine together. Told you I'll be here forever. Said I'll always be your friend. Took an oath, I'ma stick it out to the end. Now that it's raining more than ever. Know that we'll still have each other"},
                        {artist: "Justin Bieber", title: "Sorry", lyrics: "You gotta go and get angry at all of my honesty. You know I try but I don't do too well with apologies. I hope I don't run out of time, could someone call a referee?. Cause I just need one more shot at forgiveness. I know you know that I made those mistakes maybe once or twice. By once or twice I mean maybe a couple a hundred times. So let me, oh let me redeem, oh redeem, oh myself tonight. Cause I just need one more shot at second chances"},
                        {artist: "Rihanna", title: "Dont Stop The Music", lyrics: "Do you know what you started?. I just came here to party. But now we're rockin' on the dance floor, actin' naughty. Your hands around my waist. Just let the music play. We're hand in hand, chest to chest. And now we're face to face. I wanna take you away. Let's escape into the music, DJ let it play. I just can't refuse it. Like the way you do this. Keep on rockin' to it"},
                        {artist: "The Black Eyed Peas", title: "Where Is The Love", lyrics: "What's wrong with the world, mama. People livin' like they ain't got no mamas. I think the whole world's addicted to the drama. Only attracted to the things that'll bring the trauma. Overseas, yeah, we tryin' to stop terrorism. But we still got terrorists here livin'. In the USA, the big CIA. The Bloods and The Crips and the KKK"},
                        {artist: "Twenty One Pilots", title: "Heathens", lyrics: "Welcome to the room of people. Who have rooms of people that they loved one day. Docked away. Just because we check the guns at the door. Doesn't mean our brains will change from hand grenades. You'll never know the psychopath sitting next to you. You'll never know the murderer sitting next to you. You'll think, How'd I get here, sitting next to you?. But after all I've said, please don't forget"},
                        {artist: "Twenty One Pilots", title: "Stressed Out", lyrics: "I wish I found some better sounds. No one's ever heard. I wish I had a better voice. That sang some better words. I wish I found some chords. In an order that is new. I wish I didn't have to rhyme. Every time I sang. I was told when I get older. All my fears would shrink"},
                        {artist: "Dua Lipa", title: "New Rules", lyrics: "My love. He makes me feel like nobody else, nobody else. But my love. He doesn't love me so I tell myself, I tell myself. Let me hear you. One: Don't pick up the phone. You know he's only callin' 'cause he's drunk and alone. Two: Don't let him in. You'll have to kick him out again. Three: Don't be his friend. You know you're gonna wake up in his bed in the morning. And if you're under him, you ain't getting over him"},
                        {artist: "Zara Larsson", title: "Lush Life", lyrics: "I live my day as if it was the last. Live my day as if there was no past. Doin' it all night, all summer. Doin' it the way I wanna. Yeah, I'ma dance my heart out 'til the dawn. But I won't be done when mornin' comes. Doin' it all night, all summer. Gonna spend it like no other"},
                        {artist: "Bloodhound Gang", title: "Foxtrot Uniform Charlie Kilo", lyrics: "Vulcanize the whoopee stick. In the ham wallet. Cattle prod the oyster ditch. With the lap rocket. Batter dip the cranny axe. In the gut locker. Retrofit the pudding hatch. Ooh la la. With the boink swatter"},
                        {artist: "Linkin Park", title: "In the End", lyrics: "All I know. Time is a valuable thing. Watch it fly by as the pendulum swings. Watch it count down to the end of the day. The clock ticks life away. It's so unreal. It's so unreal, didn't look out below. Watch the time go right out the window. Trying to hold on, but didn't even know. I wasted it all just to watch you go"},
                        {artist: "Linkin Park", title: "Numb", lyrics: "Can't you see that you're smothering me. Holding too tightly, afraid to lose control?. 'Cause everything that you thought I would be. Has fallen apart right in front of you. (Caught in the undertow, just caught in the undertow). Every step that I take is another mistake to you. (Caught in the undertow, just caught in the undertow). And every second I waste is more than I can take"}];

        let currentSong;

        let usedSongList = [];

        function PlaySong()
        {
            document.getElementById("statusText").innerText = "";

            if (window.speechSynthesis.speaking)
            {
                if (window.speechSynthesis.paused)
                {
                    window.speechSynthesis.resume();

                    document.getElementById("playPauseIcon").innerText = "pause";
                    document.getElementById("playPauseSpan").innerText = "Pause Song";
                }
                else
                {
                    window.speechSynthesis.pause();

                    document.getElementById("playPauseIcon").innerText = "play_arrow";
                    document.getElementById("playPauseSpan").innerText = "Play Song";
                }
            }
            else
            {
                if (document.getElementById("playPauseIcon").innerText == "pause")
                {
                    window.speechSynthesis.cancel();

                    document.getElementById("playPauseIcon").innerText = "play_arrow";
                    document.getElementById("playPauseSpan").innerText = "Play Song";
                }
                else
                {
                    let speech = new SpeechSynthesisUtterance(currentSong.lyrics);
                    speech.lang = 'en-US';
                    window.speechSynthesis.speak(speech);

                    document.getElementById("playPauseIcon").innerText = "pause";
                    document.getElementById("playPauseSpan").innerText = "Pause Song";
                }
            }
        }

        function NextSong()
        {
            window.speechSynthesis.cancel();
            document.getElementById("playPauseIcon").innerText = "play_arrow";
            document.getElementById("playPauseSpan").innerText = "Play Song";

            if (songList.length <= 0)
            {
                document.getElementById("currentSongArtist").innerText = "";
                document.getElementById("currentSongTitle").innerText = "";
                document.getElementById("statusText").innerText = "No songs left, reload page for a new game";
                return;
            }

            let randomIndex = Math.floor(Math.random() * songList.length);
            currentSong = songList[randomIndex];
            usedSongList.push(songList.splice(randomIndex, 1));

            document.getElementById("currentSongArtist").innerText = "";
            document.getElementById("currentSongTitle").innerText = "";
            document.getElementById("statusText").innerText = "Next song selected, press Play";
        }

        function RevealSong()
        {
            if (document.getElementById("revealIcon").innerText == "visibility")
            {
                document.getElementById("currentSongArtist").innerText = currentSong.artist;
                document.getElementById("currentSongTitle").innerText = currentSong.title;
                document.getElementById("statusText").innerText = "";

                document.getElementById("revealIcon").innerText = "visibility_off"
                document.getElementById("revealSpan").innerText = "Hide Song";
            }
            else
            {
                document.getElementById("currentSongArtist").innerText = "";
                document.getElementById("currentSongTitle").innerText = "";
                document.getElementById("statusText").innerText = "";

                document.getElementById("revealIcon").innerText = "visibility"
                document.getElementById("revealSpan").innerText = "Reveal Song";
            }
        }

        NextSong();
    </script>
    <style>
        body
        {
            font-family: 'Roboto', sans-serif;
            background: linear-gradient(180deg, hsl(194.3181818181818,100%,45%) 0%, hsl(194.3181818181818,70%,35%) 100%);
            width: 100vw;
            height: 100vh;
            color: white;
        }
        body *
        {
            background-color: transparent;
        }
        h1
        {
            font-size: 300%;
        }
        #currentSongArtist, #currentSongTitle
        {
            font-size: 200%;
        }
        button
        {
            background-color: white;
            border: solid white 2px;
            border-radius: 6px;
        }
    </style>
</body>


</html>