<!DOCTYPE html>
<html lang="ja">
<head>
<meta charset="usf-8">
<title>Javascript Practice</title>
<style>
  body{
    display: flex;
    flex-wrap: wrap;
  }
  .box{
    width: 130px;
    height: 100px;
    background-color: skyblue;
    cursor: pointer;
    transition: 0.8s;
    margin: 0 8px 8px 0;
    text-align: center;
    line-height: 100px;
  }
  .win {
background-color: pink;
border-radius: 50%;
transform: rotate(360deg);
  }

  .lose{
transfom: scale(0.9);
  }
</style>
</head>
<body>

  <script>
    'use script';

    const num = 5;
    const winner = Math.floor(Math.random() * num); // 0 - 4

    for (let i = 0; i < num; i++) {
      const div = document.createElement('div');
      div.classList.add('box')

      div.addEventListener('click', () => {
        if ( i === winner){
          div.textContent = 'かち✨'
          div.classList.add('win');

        } else {
          div.textContent = '負け ;  ; '
          div.classList.add('lose');


        }

      })

      document.body.appendChild(div);

    }

  </script>
</body>
</html>
