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
