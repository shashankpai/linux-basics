### shutdown a system using systemctl command

<details><summary>show</summary>
<p>

```bash
systemctl reboot
```
</p>
</details>

### using shutdown command with -p flag (power off) 

<details><summary>show</summary>
<p>

```bash
shutdown -p
```
</p>
</details>

### using shutdown command with -r flag (reboot) 

<details><summary>show</summary>
<p>

```bash
shutdown -r
```
</p>
</details>

### using shutdown command with -r flag (reboot system afer 5 mins with a message) 

<details><summary>show</summary>
<p>

```bash
shutdown -r +5 System going down for a reboot
```
</p>
</details>

### cancel the scheduled reboot 

<details><summary>show</summary>
<p>

```bash
shutdown -c
```
</p>
</details>

### shut down immediately

<details><summary>show</summary>
<p>

```bash
shutdown -r now
```
</p>
</details>

### poweroff a system using systemctl halt

<details><summary>show</summary>
<p>

```bash
systemctl halt 
Or
shutdown -h now
Or
shutdown -h +5 system will be shut down in 5 mins  
```
</p>
</details>

