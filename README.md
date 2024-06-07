python main.py hide image_100KB.png --output_path output_100KB.png --message "lol" --generator fibonacci
python main.py hide image_10MB.png --output_path output_10MB.png --message "lol" --generator fibonacci
python main.py hide image_30MB.png --output_path output_30MB.png --message "lol" --generator fibonacci
python main.py reveal output_100KB.png --generator fibonacci
python main.py reveal output_10MB.png --generator fibonacci
python main.py reveal output_30MB.png --generator fibonacci
python main.py hide image_100KB.png --output_path output_100KB.png --message "lol" --generator eratosthenes
python main.py hide image_10MB.png --output_path output_10MB.png --message "lol" --generator eratosthenes
python main.py hide image_30MB.png --output_path output_30MB.png --message "lol" --generator eratosthenes
python main.py reveal output_100KB.png --generator eratosthenes
python main.py reveal output_10MB.png --generator eratosthenes
python main.py reveal output_30MB.png --generator eratosthenes


Fibonacci hide
Message hidden in output_100KB.png
Original size: 2950551 bytes, New size: 2576222 bytes
Time taken to hide the message: 0.3504149913787842 seconds

Message hidden in output_10MB.png
Original size: 8339374 bytes, New size: 9438797 bytes
Time taken to hide the message: 4.752394437789917 seconds

Message hidden in output_30MB.png
Original size: 32008355 bytes, New size: 35966068 bytes
Time taken to hide the message: 18.531571865081787 seconds


Fibonacci reveal
Secret message: lol
Time taken to reveal the message: 0.035063743591308594 seconds

Secret message: lol
Time taken to reveal the message: 0.19069671630859375 seconds

Secret message: lol
Time taken to reveal the message: 0.7089362144470215 seconds


Eratosthenes hide
Message hidden in output_100KB.png
Original size: 2950551 bytes, New size: 2576231 bytes
Time taken to hide the message: 0.35195040702819824 seconds

Message hidden in output_10MB.png
Original size: 8339374 bytes, New size: 9438795 bytes
Time taken to hide the message: 4.798036336898804 seconds

Message hidden in output_30MB.png
Original size: 32008355 bytes, New size: 35966062 bytes
Time taken to hide the message: 18.915275812149048 seconds

Eratosthenes reveal
Secret message: lol
Time taken to reveal the message: 0.03352856636047363 seconds

Secret message: lol
Time taken to reveal the message: 0.1895427703857422 seconds

Secret message: lol
Time taken to reveal the message: 0.6989860534667969 seconds
