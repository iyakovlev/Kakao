//[kakao](../../../index.md)/[io.github.kakaocup.kakao.edit](../index.md)/[EditableActions](index.md)



# EditableActions  
 [androidJvm] interface [EditableActions](index.md) : [BaseActions](../../io.github.kakaocup.kakao.common.actions/-base-actions/index.md)

Provides editable actions for views

   


## Functions  
  
|  Name |  Summary | 
|---|---|
| <a name="io.github.kakaocup.kakao.common.actions/BaseActions/act/#kotlin.Function0[androidx.test.espresso.ViewAction]/PointingToDeclaration/"></a>[act](../../io.github.kakaocup.kakao.common.actions/-base-actions/act.md)| <a name="io.github.kakaocup.kakao.common.actions/BaseActions/act/#kotlin.Function0[androidx.test.espresso.ViewAction]/PointingToDeclaration/"></a>[androidJvm]  <br>Content  <br>open fun [act](../../io.github.kakaocup.kakao.common.actions/-base-actions/act.md)(function: () -> ViewAction)  <br>More info  <br>Performs custom action on a view  <br><br><br>|
| <a name="io.github.kakaocup.kakao.edit/EditableActions/clearText/#/PointingToDeclaration/"></a>[clearText](clear-text.md)| <a name="io.github.kakaocup.kakao.edit/EditableActions/clearText/#/PointingToDeclaration/"></a>[androidJvm]  <br>Content  <br>open fun [clearText](clear-text.md)()  <br>More info  <br>Clears current text in the view  <br><br><br>|
| <a name="io.github.kakaocup.kakao.common.actions/BaseActions/click/#androidx.test.espresso.action.GeneralLocation/PointingToDeclaration/"></a>[click](../../io.github.kakaocup.kakao.common.actions/-base-actions/click.md)| <a name="io.github.kakaocup.kakao.common.actions/BaseActions/click/#androidx.test.espresso.action.GeneralLocation/PointingToDeclaration/"></a>[androidJvm]  <br>Content  <br>open fun [click](../../io.github.kakaocup.kakao.common.actions/-base-actions/click.md)(location: GeneralLocation = GeneralLocation.VISIBLE_CENTER)  <br>More info  <br>Performs click on view  <br><br><br>|
| <a name="io.github.kakaocup.kakao.common.actions/BaseActions/doubleClick/#androidx.test.espresso.action.GeneralLocation/PointingToDeclaration/"></a>[doubleClick](../../io.github.kakaocup.kakao.common.actions/-base-actions/double-click.md)| <a name="io.github.kakaocup.kakao.common.actions/BaseActions/doubleClick/#androidx.test.espresso.action.GeneralLocation/PointingToDeclaration/"></a>[androidJvm]  <br>Content  <br>open fun [doubleClick](../../io.github.kakaocup.kakao.common.actions/-base-actions/double-click.md)(location: GeneralLocation = GeneralLocation.VISIBLE_CENTER)  <br>More info  <br>Performs double click on view  <br><br><br>|
| <a name="io.github.kakaocup.kakao.common.actions/BaseActions/longClick/#androidx.test.espresso.action.GeneralLocation/PointingToDeclaration/"></a>[longClick](../../io.github.kakaocup.kakao.common.actions/-base-actions/long-click.md)| <a name="io.github.kakaocup.kakao.common.actions/BaseActions/longClick/#androidx.test.espresso.action.GeneralLocation/PointingToDeclaration/"></a>[androidJvm]  <br>Content  <br>open fun [longClick](../../io.github.kakaocup.kakao.common.actions/-base-actions/long-click.md)(location: GeneralLocation = GeneralLocation.VISIBLE_CENTER)  <br>More info  <br>Performs long click on view  <br><br><br>|
| <a name="io.github.kakaocup.kakao.common.actions/BaseActions/onFailure/#kotlin.Function2[kotlin.Throwable,org.hamcrest.Matcher[android.view.View],kotlin.Unit]/PointingToDeclaration/"></a>[onFailure](../../io.github.kakaocup.kakao.common.actions/-base-actions/on-failure.md)| <a name="io.github.kakaocup.kakao.common.actions/BaseActions/onFailure/#kotlin.Function2[kotlin.Throwable,org.hamcrest.Matcher[android.view.View],kotlin.Unit]/PointingToDeclaration/"></a>[androidJvm]  <br>Content  <br>open fun [onFailure](../../io.github.kakaocup.kakao.common.actions/-base-actions/on-failure.md)(function: (error: [Throwable](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-throwable/index.html), matcher: Matcher<[View](https://developer.android.com/reference/kotlin/android/view/View.html)>) -> [Unit](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-unit/index.html))  <br>More info  <br>Adds failure handler to the view  <br><br><br>|
| <a name="io.github.kakaocup.kakao.common.actions/BaseActions/pressImeAction/#/PointingToDeclaration/"></a>[pressImeAction](../../io.github.kakaocup.kakao.common.actions/-base-actions/press-ime-action.md)| <a name="io.github.kakaocup.kakao.common.actions/BaseActions/pressImeAction/#/PointingToDeclaration/"></a>[androidJvm]  <br>Content  <br>open fun [pressImeAction](../../io.github.kakaocup.kakao.common.actions/-base-actions/press-ime-action.md)()  <br>More info  <br>Presses IME action, if supported view is in focus  <br><br><br>|
| <a name="io.github.kakaocup.kakao.common.actions/BaseActions/repeatUntil/#kotlin.Int#kotlin.Function0[androidx.test.espresso.ViewAction]#kotlin.Function1[io.github.kakaocup.kakao.common.builders.ViewBuilder,kotlin.Unit]/PointingToDeclaration/"></a>[repeatUntil](../../io.github.kakaocup.kakao.common.actions/-base-actions/repeat-until.md)| <a name="io.github.kakaocup.kakao.common.actions/BaseActions/repeatUntil/#kotlin.Int#kotlin.Function0[androidx.test.espresso.ViewAction]#kotlin.Function1[io.github.kakaocup.kakao.common.builders.ViewBuilder,kotlin.Unit]/PointingToDeclaration/"></a>[androidJvm]  <br>Content  <br>open fun [repeatUntil](../../io.github.kakaocup.kakao.common.actions/-base-actions/repeat-until.md)(maxAttempts: [Int](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html) = 1, action: () -> ViewAction, matcher: [ViewBuilder](../../io.github.kakaocup.kakao.common.builders/-view-builder/index.md).() -> [Unit](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-unit/index.html))  <br>More info  <br>Repeats given action on the view until this view will match the given matcher  <br><br><br>|
| <a name="io.github.kakaocup.kakao.edit/EditableActions/replaceText/#kotlin.String/PointingToDeclaration/"></a>[replaceText](replace-text.md)| <a name="io.github.kakaocup.kakao.edit/EditableActions/replaceText/#kotlin.String/PointingToDeclaration/"></a>[androidJvm]  <br>Content  <br>open fun [replaceText](replace-text.md)(text: [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html))  <br>More info  <br>Replaces the current view text with given  <br><br><br>|
| <a name="io.github.kakaocup.kakao.common.actions/BaseActions/scrollTo/#/PointingToDeclaration/"></a>[scrollTo](../../io.github.kakaocup.kakao.common.actions/-base-actions/scroll-to.md)| <a name="io.github.kakaocup.kakao.common.actions/BaseActions/scrollTo/#/PointingToDeclaration/"></a>[androidJvm]  <br>Content  <br>open fun [scrollTo](../../io.github.kakaocup.kakao.common.actions/-base-actions/scroll-to.md)()  <br>More info  <br>Scrolls to the view, if possible  <br><br><br>|
| <a name="io.github.kakaocup.kakao.edit/EditableActions/typeText/#kotlin.String/PointingToDeclaration/"></a>[typeText](type-text.md)| <a name="io.github.kakaocup.kakao.edit/EditableActions/typeText/#kotlin.String/PointingToDeclaration/"></a>[androidJvm]  <br>Content  <br>open fun [typeText](type-text.md)(text: [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html))  <br>More info  <br>Types the given text into the view  <br><br><br>|


## Properties  
  
|  Name |  Summary | 
|---|---|
| <a name="io.github.kakaocup.kakao.edit/EditableActions/view/#/PointingToDeclaration/"></a>[view](index.md#-961061064%2FProperties%2F34310170)| <a name="io.github.kakaocup.kakao.edit/EditableActions/view/#/PointingToDeclaration/"></a> [androidJvm] abstract val [view](index.md#-961061064%2FProperties%2F34310170): [ViewInteractionDelegate](../../io.github.kakaocup.kakao.delegate/-view-interaction-delegate/index.md)   <br>|


## Inheritors  
  
|  Name | 
|---|
| <a name="io.github.kakaocup.kakao.edit/KEditText///PointingToDeclaration/"></a>[KEditText](../-k-edit-text/index.md)|
