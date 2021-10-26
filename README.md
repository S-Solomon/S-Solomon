```javascript
import { Solomon, Bio } from "portfolio"
import { nanoid } from 'nanoid';

class AboutMe extends Solomon.Bio {
  const getDailyKnowledge = () => {
    return (
		[
		    id: nanoid(), name: 'HTML',
		    id: nanoid(), name: 'CSS/SASS',
		    id: nanoid(), name: 'Javascript(ES6)'
		    id: nanoid(), name: 'Typescript',
		    id: nanoid(), name: 'REACT JS'
		    id: nanoid(), name: 'Algorithms & Data Structures'
		 ]
	   )
     }

    render (
      return (
	 <div>
	    {getDailyKnowledge().map(item => {
		return(
		  <div key={item.id}>
		  	<h1>{item.name}</h1>
		  </div>
		)
	    })}
	 </div>
	)
    )
}

export default AboutMe
```


[![Front‑End_Checklist followed](https://img.shields.io/badge/Front‑End_Checklist-followed-brightgreen.svg)](https://github.com/thedaviddias/Front-End-Checklist/)
