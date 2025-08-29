# BFHL API

This repository is created for the Full Stack BFHL assignment.  
The API endpoint is available at:

**POST**: https://deepika-bfhl.free.beeceptor.com/bfhl  

## Example Request
```json
{
  "data": ["a", "1", "2", "$"]
}

**## Example Response**

{
  "is_success": true,
  "user_id": "deepika_singh_29082001",
  "email": "your_email@vitbhopal.ac.in",
  "roll_number": "YOURROLL123",
  "odd_numbers": ["1"],
  "even_numbers": ["2", "4"],
  "alphabets": ["A", "B"],
  "special_characters": ["$"],
  "sum": "7",
  "concat_string": "Ba"
}

