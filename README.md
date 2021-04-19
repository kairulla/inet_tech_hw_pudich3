### Қайрулла Руслан ВТиП-202

мячик перемещается по диагонали с помощью функции ease-in-out на css

<br>
<img src="screenshots/1.png">
<br>

```
<!doctype html>
<html>
	<head>
	<title></title>
	</head>
	<body>
		<style>
            .time-animation {                
                -webkit-transition: all 2s ease-in-out;
                -moz-transition: all 2s ease-in-out;
                -o-transition: all 2s ease-in-out;
	         }
            
            #ball {
                width: 100px;
                height: 100px;
                margin: 400px auto 80px auto;
                position: relative;
                text-align: center;
            }

            #ball:hover 
            
            .diagonal-moving {
                transform: translate(350px,-350px);
                -webkit-transform: translate(350px,-350px);
                -o-transform: translate(350px,-350px); 
                -moz-transform: translate(350px,-350px);
            }
        </style>


        <div id="ball">
			<img class="time-animation diagonal-moving" src="ball.png" width="100%"/>
		</div>
	</body>
</html>

```
