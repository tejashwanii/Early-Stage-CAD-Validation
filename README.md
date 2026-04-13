# AI-Driven Design Intelligence for Early Stage CAD Validation

## Folder Structure

```text
/
|- backend/
|- cad-engine/
|- frontend/
|- shared/
```

## Setup

```bash
npm install
python -m venv .venv
.venv\Scripts\activate
pip install -r cad-engine/requirements.txt
```

`cadquery-ocp` provides the `OCP` Python modules used by the STEP loader.

## Run Locally

```bash
npm run dev --workspace backend
```

```bash
npm run dev --workspace frontend
```

Open `http://localhost:5173`.
