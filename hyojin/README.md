cd Backden
source .venv/Scripts/activate
uvicorn app.main:app --reload

cd Frontend
npm run dev
