from fastapi import FastAPI
app = FastAPI()
@app.get("/defolt")
async def root():
    return {"massege": "Hello Everyone"}
@app.get("/Ukraine")
async def root():
    return 'NEWS ABOUT UKRAINE'

@app.get("/contact")
async def contact():
    return {"message": "Contact my tg @Ja_wewykyj"}
