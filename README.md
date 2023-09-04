# LoL-Lane-Champ-picker
import random

Champions = [
    "Swain", "Diana", "Kayle", "Wukong", "Braum", "Renekton", "Malphite", "Aurelion sol", "Volibear", "Darius", "Sett", "Gwen", "Jax", "Ekko", "Shen", "Lucian", "Aatrox", "Fiora", "Yone", "Kassadin", "Teemo",
        "Master Yi", "Riven", "Zed", "Garen", "ornn", "draven", "Urgot", "Vladmir", "Yasuo", "Irelia", "Serphine", "Jinx", "Xin Xhao", "Ashe", "Pantheon", "Lee sin", "Varus", "nasus", "annie", "lux", "Ahri", "Nilah", "VI" 
]

Lane = [
    "Top", "mid", "jungle", "dragon", "support",
]

z = random.choice(Lane)
x = random.choice(Champions)

print(x)
print(z)
