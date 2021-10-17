```javascript
import { Solomon, Bio } from "portfolio"
import nanoid from "nanoid"

class AboutMe extends Solomon.Bio {
  const getDailyKnowledge = () => {
    return (
		[
		    id: nanoid(), name: 'HTML',
		    id: nanoid(), name: 'CSS/SASS',
		    id: nanoid(), name: 'Javascript(ES6)/Typescript',
		    id: nanoid(), name: 'REACT'
		 ]
	   )
     }

    render (
      return (
	 <div>
	    {getDailyKnowledge().map(item => {
		return(
		  {item.id} {item.name}
		)
	    })}
	 </div>
	)
    )
}

export default AboutMe
```


[![Front‑End_Checklist followed](https://img.shields.io/badge/Front‑End_Checklist-followed-brightgreen.svg)](https://github.com/thedaviddias/Front-End-Checklist/)
