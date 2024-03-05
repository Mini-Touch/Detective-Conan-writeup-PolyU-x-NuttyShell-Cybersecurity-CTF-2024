# Detective Conan 名偵探柯南<br> (Category: Misc, Points: 466, Solves: 17)
 Solve by T004 - Nessie explode 4

Challenge Description:
> There is only one truth! But the truth is in the past...if only there is a way back...<br>
> 真相永遠只有一個！但係真相只存在於過去...如果有部時光機就好喇...
> 
> Author 作者: PurpleSe4shell

# Tmr sin make


A .eml file given to us, and when we open it, we can see the following message:
// Please replace the photo since it capture on my devices
<img width="1440" alt="Img 01" src="https://github.com/minglol7794/CTF-writeup/assets/70463751/adcb95f8-8916-4d79-a121-71298ccf3e66">

And a photo is also attached on the email:
![seasonal_greetings](https://github.com/minglol7794/CTF-writeup/assets/70463751/57a44449-cb6d-4b4d-9ae1-f89ca4b9e5cb)

We have save the .jpg file and open the .jpg file with the hex editor, and we can saw lot of secret-directive.nuttyshell.cc on the file begining
// Please replace the photo since it capture on my devices
<img width="1423" alt="螢幕截圖 2024-03-05 下午6 40 48" src="https://github.com/minglol7794/CTF-writeup/assets/70463751/98a1bcbd-b127-424b-a020-c8dc560c7691">

We try to enter the secret-directive.nuttyshell.cc to our browser, and we found that there only have cat video and hint
"I'm hosted with GitHub Pages."
"Nothing to see here now execept cat videos.. if only there is a way back..."
// Please replace the photo since it capture on my devices
<img width="1439" alt="螢幕截圖 2024-03-05 下午6 47 05" src="https://github.com/minglol7794/CTF-writeup/assets/70463751/1eb1b0c6-9202-4d70-bfa6-ae0e0b657682">

When taking about going back, we have think of wayback machine, so we have try to enter the link to the wayback machine
but only the same pages show up
<img width="1440" alt="螢幕截圖 2024-03-05 下午6 50 53" src="https://github.com/minglol7794/CTF-writeup/assets/70463751/81a4bf23-ae71-4ec8-bbf5-120412df2aee">
