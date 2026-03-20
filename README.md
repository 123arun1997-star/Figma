# Ex08 Event Registration Web Application
## Date:20.03.2026

## AIM:
To design, develop and deploy a web application for event registration using Figma UI tool.

## UI DESIGN TOOL:
Figma

## DESIGN STEPS:

### Step 1:
Use frames to represent screens or sections.

### Step 2:
Add column grids for consistent spacing and alignment.

### Step 3:
Insert shapes, text, buttons, and icons.

### Step 4:
Use Auto Layout for flexible, responsive design.

### Step 5:
Define color, text, and effect styles globally for consistency.

### Step 6:
Name layers logically and group related elements.

### Step 6:
Link frames to show navigation or interactions.

### Step 7:
Select the specific frame while generating code using Anima plugin.

## CODE:
```
Home page:1
import ellipse3 from "./ellipse-3.png";
import rectangle1 from "./rectangle-1.png";
import rectangle2 from "./rectangle-2.svg";
import saveethaEngineeringCollegeLogo400X4001 from "./saveetha-engineering-college-logo-400x400-1.png";
import textOnAPath from "./text-on-a-path.svg";

export const IphoneProMax = (): JSX.Element => {
  return (
    <div className="overflow-hidden bg-[url(/iphone-16-17-pro-max-1.png)] bg-cover bg-[50%_50%] w-full min-w-[440px] min-h-[956px] relative">
      <img
        className="absolute top-[74px] left-0 w-[440px] h-[121px]"
        alt="Saveetha engineering"
        src={saveethaEngineeringCollegeLogo400X4001}
      />

      <img
        className="absolute top-[324px] left-[33px] w-[295px] h-[68px]"
        alt="Text on a path"
        src={textOnAPath}
      />

      <img
        className="absolute top-52 left-[-349px] w-[179px] h-[184px]"
        alt="Rectangle"
        src={rectangle1}
      />

      <div className="absolute top-[306px] left-[-370px] w-[162px] h-[100px] bg-[#d9d9d9] rounded-[81px/50px] rotate-180" />

      <img
        className="absolute top-[446px] left-24 w-[255px] h-[58px]"
        alt="Rectangle"
        src={rectangle2}
      />

      <div className="absolute top-[458px] left-[calc(50.00%_-_101px)] w-[215px] [font-family:'Irish_Grover-Regular',Helvetica] font-normal text-black text-[32px] tracking-[0] leading-[normal]">
        TOURNAMENT
      </div>

      <button
        className="absolute top-[551px] left-[113px] w-[221px] h-[59px] bg-[#09469c33] shadow-[0px_4px_4px_#00000040,inset_0_1px_0_rgba(255,255,255,0.40),inset_1px_0_0_rgba(255,255,255,0.32),inset_0_-1px_1px_rgba(0,0,0,0.13),inset_-1px_0_1px_rgba(0,0,0,0.11)] backdrop-blur-[2.0px] backdrop-brightness-[100.0%] backdrop-saturate-[100.0%] [-webkit-backdrop-filter:blur(2.0px)_brightness(100.0%)_saturate(100.0%)] cursor-pointer"
        type="button"
        aria-label="Login"
      >
        <span className="absolute top-[50%] left-[50%] translate-x-[-50%] translate-y-[-50%] [font-family:'Jaini_Purva-Regular',Helvetica] font-normal text-white text-[32px] tracking-[0] leading-[normal] whitespace-nowrap">
          LOGIN
        </span>
      </button>

      <button
        className="absolute top-[657px] left-[111px] w-[223px] h-[61px] bg-[#17309533] border border-solid border-black backdrop-blur-[2.0px] backdrop-brightness-[100.0%] backdrop-saturate-[100.0%] [-webkit-backdrop-filter:blur(2.0px)_brightness(100.0%)_saturate(100.0%)] shadow-[inset_0_1px_0_rgba(255,255,255,0.40),inset_1px_0_0_rgba(255,255,255,0.32),inset_0_-1px_1px_rgba(0,0,0,0.13),inset_-1px_0_1px_rgba(0,0,0,0.11)] cursor-pointer"
        type="button"
        aria-label="Register"
      >
        <span className="absolute top-[50%] left-[50%] translate-x-[-50%] translate-y-[-50%] [font-family:'Jaini_Purva-Regular',Helvetica] font-normal text-white text-[32px] tracking-[0] leading-[normal] whitespace-nowrap">
          REGISTER
        </span>
      </button>

      <div className="absolute top-[227px] left-[152px] w-[5px] h-[9px] bg-[#d9d9d9] rounded-[2.5px/4.5px]" />

      <img
        className="absolute top-[227px] left-[113px] w-[223px] h-[179px]"
        alt="Ellipse"
        src={ellipse3}
      />
    </div>
  );
};

page:2

import rectangle5 from "./rectangle-5.svg";

export const Box = (): JSX.Element => {
  return (
    <div className="w-[369px] h-[82px]">
      <img
        className="fixed top-0 left-0 w-[369px] h-[82px]"
        alt="Rectangle"
        src={rectangle5}
      />
    </div>
  );
};

page:3

import { useState } from "react";
import rectangle15 from "./rectangle-15.svg";

export const IphoneProMax = (): JSX.Element => {
  const [formData, setFormData] = useState({
    fullName: "",
    age: "",
    emailId: "",
    phoneNo: "",
    district: "",
    squadName: "",
  });

  const handleChange = (e: React.ChangeEvent<HTMLInputElement>) => {
    const { name, value } = e.target;
    setFormData((prev) => ({ ...prev, [name]: value }));
  };

  const handleSubmit = (e: React.FormEvent<HTMLFormElement>) => {
    e.preventDefault();
  };

  return (
    <div className="relative w-[440px] h-[956px] mix-blend-exclusion bg-blend-darken bg-[url(/iphone-16-17-pro-max-3.png)] bg-cover bg-[50%_50%]">
      <form onSubmit={handleSubmit}>
        {/* Title Banner */}
        <div className="absolute top-[42px] left-[34px] w-[371px] h-[75px] bg-[#d9d9d933] border border-solid border-white shadow-[0px_4px_4px_#00000040,inset_0_1px_0_rgba(255,255,255,0.40),inset_1px_0_0_rgba(255,255,255,0.32),inset_0_-1px_1px_rgba(0,0,0,0.13),inset_-1px_0_1px_rgba(0,0,0,0.11)] backdrop-blur-[2.0px] backdrop-brightness-[100.0%] backdrop-saturate-[100.0%] [-webkit-backdrop-filter:blur(2.0px)_brightness(100.0%)_saturate(100.0%)] flex items-center justify-center" />
        <div className="absolute top-14 left-14 [font-family:'Jaini_Purva-Regular',Helvetica] font-normal text-[#edff00] text-4xl tracking-[0] leading-[normal] pointer-events-none">
          EVENT REGISTRATION FORM
        </div>

        {/* Full Name Field */}
        <div className="absolute top-[158px] left-[34px] w-[371px] h-[78px] bg-[#d9d9d933] border border-solid border-[#f3f0f0] backdrop-blur-[2.0px] backdrop-brightness-[100.0%] backdrop-saturate-[100.0%] [-webkit-backdrop-filter:blur(2.0px)_brightness(100.0%)_saturate(100.0%)] shadow-[inset_0_1px_0_rgba(255,255,255,0.40),inset_1px_0_0_rgba(255,255,255,0.32),inset_0_-1px_1px_rgba(0,0,0,0.13),inset_-1px_0_1px_rgba(0,0,0,0.11)]" />
        <label
          htmlFor="fullName"
          className="absolute top-[173px] left-14 [font-family:'Jaini_Purva-Regular',Helvetica] font-normal text-black text-4xl tracking-[0] leading-[normal] pointer-events-none"
        >
          Full Name :
        </label>
        <input
          id="fullName"
          name="fullName"
          type="text"
          value={formData.fullName}
          onChange={handleChange}
          className="absolute top-[158px] left-[34px] w-[371px] h-[78px] bg-transparent border-0 outline-none pl-[120px] pr-4 [font-family:'Jaini_Purva-Regular',Helvetica] font-normal text-black text-4xl tracking-[0] leading-[normal]"
          aria-label="Full Name"
        />

        {/* Age Field */}
        <div className="absolute top-[282px] left-[34px] w-[371px] h-[81px] bg-[#f6f6f033] border border-solid border-[#ddff00] backdrop-blur-[2.0px] backdrop-brightness-[100.0%] backdrop-saturate-[100.0%] [-webkit-backdrop-filter:blur(2.0px)_brightness(100.0%)_saturate(100.0%)] shadow-[inset_0_1px_0_rgba(255,255,255,0.40),inset_1px_0_0_rgba(255,255,255,0.32),inset_0_-1px_1px_rgba(0,0,0,0.13),inset_-1px_0_1px_rgba(0,0,0,0.11)] opacity-10" />
        <div className="absolute top-[282px] left-9 w-[374px] h-[81px] bg-[#d9d9d933] border border-solid border-transparent backdrop-blur-[2.0px] backdrop-brightness-[100.0%] backdrop-saturate-[100.0%] [-webkit-backdrop-filter:blur(2.0px)_brightness(100.0%)_saturate(100.0%)] shadow-[inset_0_1px_0_rgba(255,255,255,0.40),inset_1px_0_0_rgba(255,255,255,0.32),inset_0_-1px_1px_rgba(0,0,0,0.13),inset_-1px_0_1px_rgba(0,0,0,0.11)]" />
        <label
          htmlFor="age"
          className="absolute top-[299px] left-14 [font-family:'Jaini_Purva-Regular',Helvetica] font-normal text-black text-4xl tracking-[0] leading-[normal] pointer-events-none"
        >
          Age:
        </label>
        <input
          id="age"
          name="age"
          type="number"
          value={formData.age}
          onChange={handleChange}
          className="absolute top-[282px] left-9 w-[374px] h-[81px] bg-transparent border-0 outline-none pl-[90px] pr-4 [font-family:'Jaini_Purva-Regular',Helvetica] font-normal text-black text-4xl tracking-[0] leading-[normal]"
          aria-label="Age"
        />

        {/* Email ID Field */}
        <img
          className="absolute top-[397px] left-[42px] w-[368px] h-[83px]"
          alt="Rectangle"
          src={rectangle15}
        />
        <label
          htmlFor="emailId"
          className="absolute top-[415px] left-14 [font-family:'Jaini_Purva-Regular',Helvetica] font-normal text-black text-4xl tracking-[0] leading-[normal] pointer-events-none"
        >
          Email ID :
        </label>
        <input
          id="emailId"
          name="emailId"
          type="email"
          value={formData.emailId}
          onChange={handleChange}
          className="absolute top-[397px] left-[42px] w-[368px] h-[83px] bg-transparent border-0 outline-none pl-[160px] pr-4 [font-family:'Jaini_Purva-Regular',Helvetica] font-normal text-black text-4xl tracking-[0] leading-[normal]"
          aria-label="Email ID"
        />

        {/* Phone No Field */}
        <div className="absolute top-[516px] left-9 w-[364px] h-[82px] bg-[#d9d9d933] border border-solid border-[#fff7f7] shadow-[0px_4px_4px_#00000040,inset_0_1px_0_rgba(255,255,255,0.40),inset_1px_0_0_rgba(255,255,255,0.32),inset_0_-1px_1px_rgba(0,0,0,0.13),inset_-1px_0_1px_rgba(0,0,0,0.11)] backdrop-blur-[2.0px] backdrop-brightness-[100.0%] backdrop-saturate-[100.0%] [-webkit-backdrop-filter:blur(2.0px)_brightness(100.0%)_saturate(100.0%)]" />
        <div className="absolute top-[544px] left-[102px] [font-family:'Jaini_Purva-Regular',Helvetica] font-normal text-black text-4xl tracking-[0] leading-[normal] pointer-events-none">
          :
        </div>
        <label
          htmlFor="phoneNo"
          className="absolute top-[535px] left-[50px] [font-family:'Jaini_Purva-Regular',Helvetica] font-normal text-black text-4xl tracking-[0] leading-[normal] pointer-events-none"
        >
          Phone No:
        </label>
        <input
          id="phoneNo"
          name="phoneNo"
          type="tel"
          value={formData.phoneNo}
          onChange={handleChange}
          className="absolute top-[516px] left-9 w-[364px] h-[82px] bg-transparent border-0 outline-none pl-[175px] pr-4 [font-family:'Jaini_Purva-Regular',Helvetica] font-normal text-black text-4xl tracking-[0] leading-[normal]"
          aria-label="Phone No"
        />

        {/* District Field */}
        <div className="absolute top-[630px] left-[42px] w-[363px] h-[83px] bg-[#d9d9d933] border border-solid border-[#fff9f9] backdrop-blur-[2.0px] backdrop-brightness-[100.0%] backdrop-saturate-[100.0%] [-webkit-backdrop-filter:blur(2.0px)_brightness(100.0%)_saturate(100.0%)] shadow-[inset_0_1px_0_rgba(255,255,255,0.40),inset_1px_0_0_rgba(255,255,255,0.32),inset_0_-1px_1px_rgba(0,0,0,0.13),inset_-1px_0_1px_rgba(0,0,0,0.11)]" />
        <label
          htmlFor="district"
          className="absolute top-[642px] left-[61px] [font-family:'Jaini_Purva-Regular',Helvetica] font-normal text-black text-4xl tracking-[0] leading-[normal] pointer-events-none"
        >
          District :
        </label>
        <input
          id="district"
          name="district"
          type="text"
          value={formData.district}
          onChange={handleChange}
          className="absolute top-[630px] left-[42px] w-[363px] h-[83px] bg-transparent border-0 outline-none pl-[155px] pr-4 [font-family:'Jaini_Purva-Regular',Helvetica] font-normal text-black text-4xl tracking-[0] leading-[normal]"
          aria-label="District"
        />

        {/* Squad Name Field */}
        <div className="absolute top-[768px] left-[42px] w-[374px] h-[83px] bg-[#d9d9d933] backdrop-blur-[2.0px] backdrop-brightness-[100.0%] backdrop-saturate-[100.0%] [-webkit-backdrop-filter:blur(2.0px)_brightness(100.0%)_saturate(100.0%)] shadow-[inset_0_1px_0_rgba(255,255,255,0.40),inset_1px_0_0_rgba(255,255,255,0.32),inset_0_-1px_1px_rgba(0,0,0,0.13),inset_-1px_0_1px_rgba(0,0,0,0.11)]" />
        <label
          htmlFor="squadName"
          className="absolute top-[782px] left-[53px] [font-family:'Jaini_Purva-Regular',Helvetica] font-normal text-black text-4xl tracking-[0] leading-[normal] pointer-events-none"
        >
          Squad Name :
        </label>
        <input
          id="squadName"
          name="squadName"
          type="text"
          value={formData.squadName}
          onChange={handleChange}
          className="absolute top-[768px] left-[42px] w-[374px] h-[83px] bg-transparent border-0 outline-none pl-[200px] pr-4 [font-family:'Jaini_Purva-Regular',Helvetica] font-normal text-black text-4xl tracking-[0] leading-[normal]"
          aria-label="Squad Name"
        />
      </form>
    </div>
  );
};

page:4

import rectangle20 from "./rectangle-20.png";
import rectangle23 from "./rectangle-23.svg";

export const IphoneProMax = (): JSX.Element => {
  return (
    <div className="overflow-hidden bg-[url(/iphone-16-17-pro-max-4.png)] bg-cover bg-[50%_50%] w-full min-w-[440px] min-h-[956px] relative">
      <img
        className="absolute top-[76px] left-4 w-[408px] h-[137px] object-cover"
        alt="Rectangle"
        src={rectangle20}
      />

      <div className="absolute top-[294px] left-[38px] [font-family:'Jaini_Purva-Regular',Helvetica] font-normal text-black text-8xl tracking-[0] leading-[normal]">
        THANK YOU
      </div>

      <div className="absolute top-[316px] left-4 w-[408px] h-[104px] bg-[#d9d9d933] backdrop-blur-[2.0px] backdrop-brightness-[100.0%] backdrop-saturate-[100.0%] [-webkit-backdrop-filter:blur(2.0px)_brightness(100.0%)_saturate(100.0%)] shadow-[inset_0_1px_0_rgba(255,255,255,0.40),inset_1px_0_0_rgba(255,255,255,0.32),inset_0_-1px_1px_rgba(0,0,0,0.13),inset_-1px_0_1px_rgba(0,0,0,0.11)]" />

      <p className="absolute top-[530px] left-[calc(50.00%_-_182px)] w-[386px] [font-family:'Jaini_Purva-Regular',Helvetica] font-normal text-black text-4xl tracking-[0] leading-[normal]">
        We are all eagerly waiting for your participte in the&nbsp;&nbsp;free
        fire tournament .
      </p>

      <div className="absolute top-[478px] left-[503px] w-[166px] h-[180px] bg-[#fc1fbd33] backdrop-blur-[2.0px] backdrop-brightness-[100.0%] backdrop-saturate-[100.0%] [-webkit-backdrop-filter:blur(2.0px)_brightness(100.0%)_saturate(100.0%)] shadow-[inset_0_1px_0_rgba(255,255,255,0.40),inset_1px_0_0_rgba(255,255,255,0.32),inset_0_-1px_1px_rgba(0,0,0,0.13),inset_-1px_0_1px_rgba(0,0,0,0.11)]" />

      <img
        className="absolute top-[726px] left-[3px] w-[436px] h-[230px]"
        alt="Rectangle"
        src={rectangle23}
      />

      <div className="absolute top-[854px] left-[103px] [font-family:'Jaini_Purva-Regular',Helvetica] font-normal text-white text-[32px] tracking-[0] leading-[normal]">
        Phone No: 876543287
        <br />
        &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;
        7656765435
      </div>

      <div className="absolute top-[809px] left-[38px] [font-family:'Jaini_Purva-Regular',Helvetica] font-normal text-white text-2xl tracking-[0] leading-[normal]">
        email no : freefiereindiaofficial@gmail.com
      </div>

      <div className="absolute top-[726px] left-[91px] [font-family:'Jaini_Purva-Regular',Helvetica] font-normal text-white text-[64px] tracking-[0] leading-[normal]">
        Contact us :
      </div>
    </div>
  );
};
```



## OUTPUT:
![alt text](<Screenshot (18).png>)
![alt text](<Screenshot (19).png>)
![alt text](<Screenshot (20).png>)
![alt text](<Screenshot (21).png>)

## RESULT:
The program to design, develop and deploy a web application for event registration using Figma UI tool is completed successfully.
