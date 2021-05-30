# Instagram-Tool
✨ INSTAGRAM TOOL ~ FULL SOURCE ☁️
![Image](https://i.imgur.com/y4phlpa.png)

# instagram-tool

Functionality: 

- **Info**: Show report

- **Follow users**: from tag, from location, from a list or follow back who you do not follow back

- **Unfollow users**: who do not follow you back or all of them

---------------------

## Examples on HOW TO USE:

*python main.py -u USERNAME -p PASSWORD -o follow-tag -t wolf* : **Follow users using the tag 'wolf'** 

*python main.py -u USERNAME -p PASSWORD -o follow-location -t XXXXXXXX* : **Follow users from the location** 

*python main.py -u USERNAME -p PASSWORD -o super-followback*: **Now you are following users you didn't follow but they followed you**

*python main.py -u USERNAME -p PASSWORD -o follow-list -t userlist.txt* : **Follow users in each line of userlist.txt** 

*python main.py -u USERNAME -p PASSWORD -o super-unfollow*: **Now you are not following users who don't follow you**

---------------------

## Usage: 

**Shows (who follows, unfollows, follows you back):**
```
python main.py -u USERNAME -p PASSWORD -o info
```

**Follow users using the tag you introduce:**

```
python main.py -u USERNAME -p PASSWORD -o follow-tag -t TAG
```

**Follow users from certain location:**

```
python main.py -u USERNAME -p PASSWORD -o follow-location -t LOCATION_ID
```

**Follow back all users who you don't follow back:**
```
python main.py -u USERNAME -p PASSWORD -o super-followback
```

**Follow users from a list:**

```
python main.py -u USERNAME -p PASSWORD -o follow-list -t USER_LIST
```

**Unfollow all the users who don't follow you back:**
```
python main.py -u USERNAME -p PASSWORD -o super-unfollow
```
**NOTE**: Fill "whitelist.txt" file with the accounts you will never want to unfollow


**Unfollow all the users:**
```
python main.py -u USERNAME -p PASSWORD -o unfollow-all
```
**NOTE**: Fill "whitelist.txt" file with the accounts you will never want to unfollow

---------------------

## Note

Tested in Python 3
