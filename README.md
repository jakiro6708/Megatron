## Setup instruction

### Method 1 - Clone this repo directly

1. Clone this repo:

	```bash
	rm -rf package/megatron
	git clone https://github.com/jakiro6708/megatron.git package/megatron
	```

2. Pull upstream commits:

	```bash
	git -C package/megatron pull
	```

- Remove

  ```bash
  rm -rf package/megatron
  ```

### Git config

	git config --global user.name "Account"
	git config --global user.email "Emails"
	ssh-keygen -t rsa
	git add .
	git commit -m "$(date)" && git push
	git status