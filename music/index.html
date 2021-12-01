<!DOCTYPE html>
<html>
<head>
    <meta charset="utf-8">
    <meta name="viewport" content="width=device-width, initial-scale=1">
    <title>YT music</title>
</head>
<body>
    <input type="text" id="txtVideoId" value="KgOtLOUdCMQ"></input>
    <button type="button" onclick="playMusic()">play</button>
    <audio id="audio" controls="controls">
        <source id="audioSource" src=""></source>
        Your browser does not support the audio format.
    </audio>

    <script>
        var audio = document.getElementById('audio');
        var source = document.getElementById('audioSource');
        var nextVideoId;

        audio.onended = function() {
            if (nextVideoId) {
                play(nextVideoId);
            }
        }

        function playMusic() {
            var videoId = document.getElementById("txtVideoId").value;
            play(videoId);
        }

        function play(videoId) {
            fetch('https://chichi-music-api.herokuapp.com/audio/' + videoId)
                .then(response => response.json())
                .then(handleApiResponse);
        }

        function handleApiResponse(res) {
            // console.log(res)
            if (res.success) {
                source.src = res.data.url;
                nextVideoId = res.data.next_video_id;
                // console.log(source.src)

                audio.load(); //call this to just preload the audio without playing
                audio.play(); //call this to play the song right away
            }
            else {
                alert(res.message)
            }
        }
  </script>
</body>
</html>
