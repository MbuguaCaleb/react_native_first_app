**Mastering React**

```
(a)React is a javascript library for building user interfaces.

(b)React has been typically used for web development this being enabled
by a react library called ReactDom.render() that can be able to convert the
components in a way that they can be rendered to the browser.

(c)Intrestingly react itself is platform agnostic meaning that in exactly the same
way reacr dom render is used in the browser for web components react native can be used
to render the same components into native components for android and ios.

{
    react can be used in any platform..react is good for states and components and detecting
    the change of state.

    React js knows how to update a user interface.It knows how to control a user interface as well.
}

```

**My take**

```
The same way that i use react, components and render into web application via reacDom render is the
same way that i use reactNative and employ react to create native applications.

{ brings in special components that may be used from within react and thus rendered into a real native mobile application }

```

**React Native**

```
(a)React native on the other hand is a separate react library.{It is more like react dom the only  difference being that it is specializing on rendering react components to mobile instead.}

(b)It is a collection of React Componets.These components are compiled into native widgets.
{
    It has unique components since here there will be no divs like in web}
}

(c)React native grants you access to native platform API(s) eposed to javascript.example the device camera.

(d)connects javascript and native platform code..[You code with javscript for developing native mobile applications at a more advanced level this may be achieved.]

(e)Connecting react native which is a collection of mobile UI Components that can be used with react gives you the ability to create a mobile application that can run in any platform
either in IOS or in Android.

```

**Behind the scenes**

```
(a)Wow instead of returning divs as i would do in react...i am returning native componets.


Instead of returning divs we return speacial components.

const App = props =>{

return(
    <View>
    <Text>Hello there! </Text>
    </View>
)

}

React native brings in special components that are converted to native code.
This is what is returned instead of divs

Components are wrapped in views when building mobile applications.

(b)Javascript is the language used in developing react native applications...javascript is used to manage your business code...the views returned from within your components are compiled into real native applications.This makes react native have high performance since a large chunk of it is real native code.

```

**Comparisons**

| React for the Web | Native Component(Android) | Native Component(Android) | React Native |
| ----------------- | :-----------------------: | ------------------------: | -----------: |
| div               |       android.view        |                    UIView |         View |
| input             |         EditText          |               UITextField |    Textinput |

```
Javascript handles all the business logic example camera api and all other functionalities.

Views in React Native is what is converted into business logic

Javascript is not converted into native code there is a minithread that runs you js code through a bridge via react native.

Only the native widgets are compled(Views)

React native converts the react components into native widgets

Javascript is not converted into the native widgtes...It runs separately from within the application.
```

**EXPO VS REACT NATIVE CLI**

```

There are two options for creating a react nativa application.

Which approach should i use and why??



(a)EXPO CLI/TOOL

Gives you a managed work develpment workflow.
Simplifees the process which can be complex when using pure react native
Abstrats some of the complexity

PROS
1)Third part service and free
2)Managed app development
3)Brings in Lots of convenience and utilty features.

CONS
You are limited to expo ecosystem,
Expo is favourable for smaller applications.


REACT NATIVE CLI

You have a barebone react native app.
You have full control.
This is better for complex applications.
It is easier to connect to native android.


(a)By react Native Team/Community.

(b)Bare-bone developement as you begin your application is privided when you use expo.

(c)There is almost no Convenience or Utility features.

(d)Full flexibitly.{You can seemlesy integrate with native code}

It is possible to switch from expo to react native CLI which is a great advantage.


```

**How expo works**

```
(a)You have your simulator..where you have installed the expo client

(b)You have your react native app.

(c)Your app which you are making is leaded into expo app..

{

Expo is great for development since it allows you publish apps that do not need
to be loaded to the playstore initially.

If there is a need expo can also run or publish standalone applications which are
the applications that clients use and they do not need to have expo installed.

You may also always switch to a non-expo development workflow.
}
```

**Notes by**

```
Mbugua Caleb

```
