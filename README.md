## API Parameters

FastAPI lets you declare and validate request parameters—path, query, header, cookie, and body—directly in your function signatures:

- **Path Parameters** (`/items/{item_id}`): Extract values from the URL path.
- **Query Parameters** (`?q=search`): Define optional or required key-value inputs.
- **Request Body** (`POST`, `PUT`): Use Pydantic models to automatically parse, validate, and document JSON payloads.
- **Header & Cookie Parameters**: Annotate function args with `Header()` or `Cookie()` for extra metadata.

**Highlights:**  
- Automatic data validation & conversion  
- Built-in OpenAPI docs generation (`/docs`, `/redoc`)  
- Clear, type-annotated function signatures  
