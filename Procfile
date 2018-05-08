worker: python Potato.py

import os
import discord
from discord.ext import commands
from discord.ext.commands import Bot
import asyncio
import datetime
import chalk


bot = commands.Bot(command_prefix='Potato!')

@bot.event
async def on_ready():
    print ("Tomatoes are awful.")
    print ("I am running on " + bot.user.name)
    print ("With the ID: " + bot.user.id)

@bot.command(pass_context=True)
async def scarystoryA(ctx):
    await bot.say("Once upon a time, there was a Potato, who loved to play with his friends. Then one day, he got run over by a Potato Car! Now, his Potato spirit wakes up at sunset, and haunts all of his friends and family. His next victim - YOU!!")

@bot.command(pass_context=True)
async def scarystoryB(ctx):
    await bot.say("One day, there was a Potato heading to PotatoCorp to start his day at work. He must wake up at 5 AM to get to work. When he got in his car, his car would not start. He finally jabbed the key into the key hole and the car started. The car had a red glow to it. The Potato went to check it out. When he got close to the car, the car turned around and growled at him. The Potato tried to run away, but the car ate him! When the Potato came out, he had the body of a car, with black gas bubbles on the sides of his head. Now, he lives his life as a mutated Potato Car, and he comes to haunt people around the city. His next victim.... YOU!!")

@bot.command(pass_context=True)
async def scarystoryC(ctx):
    await bot.say("One day, a Potato was on his computer playing Five Nights at Potato Freddy's. All of a sudden, the lights went out. Then, he heard a robotic scream from his mom's room. The Potato quickly ran into his moms room to see his mom going into an animatronic's mouth! He then saw the animatronic vomiting his mom out of its mouth. When the Potato's mom turned around, she had red eyes, robotic parts inbetween her arms and legs! Her ears were on the top of her head, and her mouth was red and bloody! The Potato ran for his room, but the mom caught up and ate him! Now, The mom haunts everyone and steals their computers. Her next victim - YOU!!")

@bot.command(pass_context=True)
async def hello(ctx):
    await bot.say("Hello! I'm a Potato! -Farts-")

@bot.command(pass_context=True)
async def bye(ctx):
    await bot.say("Goodbye, Potato Friend! I'll miss you!")

bot.run(os.getenv(TOKEN))
