facts = [
    "alice_has_umbrella.",
    "sunny_day.",
    "mike_missed_the_bus.",
    "lucy_plays_tennis.",
    "it_is_windy."
]

def verify_fact(fact):
    fact = fact.rstrip(".")
    if fact == "alice_has_umbrella":
        return True
    elif fact == "sunny_day":
        return True
    elif fact == "rainy":
        return False
    elif fact == "cloudy":
        return False
    else:
        return False

for fact in facts:
    if verify_fact(fact):
        print(f"{fact} - Yes")
    else:
        print(f"{fact} - No")
