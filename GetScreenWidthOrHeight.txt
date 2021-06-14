//width
float screenWidth = 1 / (GameObject.Find("Main Camera").GetComponent<Camera>().WorldToViewportPoint(new Vector3(1, 1, 0)).x - 0.5f);
//height
float screenHeight = 1 / (GameObject.Find("Main Camera").GetComponent<Camera>().WorldToViewportPoint(new Vector3(1, 1, 0)).y - 0.5f);