```javascript
import { Harnish, Bio } from "portfolio"

class AboutMe extends Harnish.Bio {
  const getDailyKnowledge = () => {
    return (
		[
		    id: 1, name: 'SCSS',
		    id: 2, name: 'JavaScript',
		    id: 3, name: 'React',
		    id: 4, name: 'GSAP'
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

### Hi there 👋, I'm Samuel Solomon


- [![Front‑End_Checklist followed](https://img.shields.io/badge/Front‑End_Checklist-followed-brightgreen.svg)](https://github.com/thedaviddias/Front-End-Checklist/)
