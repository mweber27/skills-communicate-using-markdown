# Header 1
## Header 2
### Header 3
#### Header 4
##### Header 5
###### Header 6

# Step 2
### Image insert test

![An image of Yosemite National park](https://madera.objects.liquidweb.services/photos/20371-yosemite-may-yosemite-falls-waterfalls-cooks-meadow-spring-2023-1200x800.jpg)

# Step 3
### Add a code snippet

```{python}
def total_value(hand):
    value = 0
    aces = 0
    
    for card in hand:
        if card in ["J", "Q", "K"]:
            value += 10
        elif card == "A":
            aces += 1
        else:
            value += int(card)
    
    # Handle Aces last
    for _ in range(aces):
        if value + 11 <= 21:
            value += 11
        else:
            value += 1

    print(value)
```

# Step 4
### Add a task list

- [x] Turn on GitHub Pages
- [x] Outline my portfolio
- [ ] Introduce myself to the world
