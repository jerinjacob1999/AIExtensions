# Particles 

> Create particles animation in your app or game
>
> ![Extension](_media/ext.png)
>
> `Permission : READ_EXTERNAL_STORAGE`
>
> `Price: $6 => 390RS`
>
> `size: 50.8kb`



Using this extension you can create amazing particles /confetti animation in your app. Below are some samples:

| <img src="_media\rain.gif" style="zoom:25%;" /> | <img src="_media\point.gif" alt="point" style="zoom:22%;" /> | <img src="_media\explo.gif" alt="point" style="zoom:22%;" /> |
| :---------------------------------------------: | ------------------------------------------------------------ | ------------------------------------------------------------ |
|         Raining with draggable confetti         | Point animation                                              | Explosion animation                                          |



# Functions

```1.InitializePosition```

<!-- tabs:start -->


#### **Block image**

<img src="_media/f1.png" style="zoom:100%;" />

#### **Description**

For **point** particle emission use only x and y.

<img src="_media/g1.png" style="zoom:30%;" />

For particles to emit from a square eg: Raining in above gif, x,y,x1,y1 should be initialized

<img src="_media/g2.png" style="zoom:30%;" />

?> Note:1. InitializePostion first.<br> 2. Either x,y or both 4 variable should be initialized .

#### **Sample**

[sample](confetti?id=samples)

<!-- tabs:end -->

```2.InitializeConfetti```

<!-- tabs:start -->


#### **Block image**

<img src="_media/f2.png" style="zoom:100%;" />

#### **Description**

This blocks initialize the confetti

**layout:**` Any arrangement except scroll arrangements`

**colors**: `make a list of colors`

**images**:` make a list of images with path to image`



?> Note:1. InitializeConfetti second.<br> 2. At least colors list or images list should present  .

#### **Sample**

[sample](confetti?id=samples)

<!-- tabs:end -->



`3.Animation modes`

<!-- tabs:start -->


#### **Block image**

<img src="_media/f3.png" style="zoom:100%;" />

#### **Description**

This blocks animates particles by different methods as you see [here](confetti?id=particles)

**RainingMode:**` Creates a rainnig like animation`

**PointMode**: `Creates animation from a point`

**ExplosionMode**:` Create a explosion with a defined radius/bound`

Properties

| **RainingMode** | **PointMode** | ExplosionMode |
| --------------- | ------------- | ------------- |
| ExplosionMode   | ExplosionMode | ExplosionMode |

?> Note:1. After confetti initialized call any one of this function.<br>



#### **Related Properties**

![](_media\velocity.PNG)

For finding default values for  animation modes hover over it

![](_media\hover.png)

#### **Sample**

[sample](confetti?id=samples)

<!-- tabs:end -->

```4.Emission Modes```

<!-- tabs:start -->


#### **Block image**

<img src="_media/f4.png" style="zoom:100%;" />

#### **Description**

This blocks helps to animate particles for specified duration

**OneShot:** ` Creates a one shot like animation`

**Stream**: `Creates animates for the provided duration`

**Infinte**: ` Create a infinite stream of particles.\n After setting any mode.`

Properties

| **RainingMode** | **PointMode** | ExplosionMode |
| --------------- | ------------- | ------------- |
| ExplosionMode   | ExplosionMode | ExplosionMode |

?> Note:1. After animation modes call any one emission mode function.<br>



#### **Related Properties**

<img src="_media/p1.png" style="zoom:100%;" /> 

#### **Sample**

[sample](confetti?id=samples)

<!-- tabs:end -->



`5.Terminate`

<img src="_media/f5.png" style="zoom:100%;" />

**Terminate**: `Terminates latest running animation`

# Properties

<!-- tabs:start -->

#### **Main Properties**

<img src="_media/p.png" style="zoom:100%;" />

`ConfettiSize` :This defines size of particles.

`TimeToLeave`: Specifies a custom time to live (in `millisecond` )for the confetti generated . When a confetti reaches its time to live timer, it will disappear and terminate its animation.

`EmissionRate`:  The rate of emission particle per second
`EnableFadeout`: Enables or disables fade out animation to particles when leaving the screen.

`EnableTouch`: Enables or disables touch events for the confetti generated . By enabling touch, the user can touch individual particle and drag/fling them on the screen.

`![](_media\enables.PNG)



#### **Other**

![](_media\other.png)

For finding default values for  animation modes hover over it

![](_media\hover.png)

#### **Sample**

[sample](confetti?id=samples)



<!-- tabs:end -->

# Samples

These re some example blocks

| ![](_media\eg1.png) | ![](_media\eg2.png) | ![](_media\eg3.png) |
| ------------------- | ------------------- | ------------------- |
| Explosion           | Raining             | Point               |


# Buy Now



|                        Chec.io(`$6`)                         | Paypal(Contact [me](mailto:123jerinjacob007@gmail.com) after payment) - `$6` | [FREE](https://casagbic.com) | Paytm(Contact [me](mailto:123jerinjacob007@gmail.com) after payment) |
| :----------------------------------------------------------: | :----------------------------------------------------------: | ---------------------------- | :----------------------------------------------------------: |
| [<img src="https://dashboard.chec.io/public/images/chec.logo.dark.png" style="zoom: 35%;" />](https://checkout.chec.io/particles) | [![paypal](https://www.paypalobjects.com/en_GB/i/btn/btn_buynowCC_LG.gif)](https://www.paypal.com/cgi-bin/webscr?cmd=_s-xclick&hosted_button_id=TPPHBJDVJJA2Y) | [FREE](https://casagbic.com) | [<img src="_media/paytm.png" alt="paypal" style="zoom: 15%;" />](https://p-y.tm/ho-fKyi) |



-----