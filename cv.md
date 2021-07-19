**1. Name: **

Sergey Levchuk

2. E-mail:

serlevchuk@yandex.ru

3. Brief information about yourself

Created a project of a logging machine simulator in the "Unity" environment in the C#, I am studying javascript, I am striving to become a Frontend developer, I have the ability to quickly learn new material, since the field of programming is interesting to me. I also plan to learn the Ruby-on-Rails network.

4. My Skills

C# Junior, Ruby-I studied it myself, now studying Javascript

5. Code example

C#:

private void MoveHor() {

  if (!Input.anyKey) return;

  if (Input.GetKey(_keyToMoveLeft) && IsCanMove(_horTrRight, Vector3.left * Time.deltaTime * _speed))

  _horTrRight.localPosition += Vector3.left * Time.deltaTime * _speed;

  if (Input.GetKey(_keyToMoveRight) && IsCanMove(_horTrRight, Vector3.right * Time.deltaTime * _speed))

  _horTrRight.localPosition += Vector3.right * Time.deltaTime * _speed;

  if (Input.GetKey(_keyToMoveLeftSecond) && IsCanMove(_horTrLeft, Vector3.left * Time.deltaTime * _speed))

  _horTrLeft.localPosition += Vector3.left * Time.deltaTime * _speed;

  if (Input.GetKey(_keyToMoveRightSecond) && IsCanMove(_horTrLeft, Vector3.right * Time.deltaTime * _speed))

  _horTrLeft.localPosition += Vector3.right * Time.deltaTime * _speed;

  _horTrRight.rotation = Quaternion.Euler(0, 0, _horTrRight.localPosition.x < 0 ? 90 : -90.0f);
                                                                             
  _horTrLeft.rotation = Quaternion.Euler(0, 0, _horTrLeft.localPosition.x < 0 ? 90 : -90.0f);

}

private void MoveVer() {

  if (!Input.anyKey) return;

  if (Input.GetKey(_keyToMoveUp) && IsCanMove(_verTrRight, Vector3.up * Time.deltaTime * _speed))

  _verTrRight.localPosition += Vector3.up * Time.deltaTime * _speed;

  if (Input.GetKey(_keyToMoveDown) && IsCanMove(_verTrRight, Vector3.down * Time.deltaTime * _speed))

  _verTrRight.localPosition += Vector3.down * Time.deltaTime * _speed;

  if (Input.GetKey(_keyToMoveUpSecond) && IsCanMove(_verTrLeft, Vector3.up * Time.deltaTime * _speed))

  _verTrLeft.localPosition += Vector3.up * Time.deltaTime * _speed;

  if (Input.GetKey(_keyToMoveDownSecond) && IsCanMove(_verTrLeft, Vector3.down * Time.deltaTime * _speed))

  _verTrLeft.localPosition += Vector3.down * Time.deltaTime * _speed;

  _verTrRight.rotation = Quaternion.Euler(0, 0, _verTrRight.localPosition.y < 0 ? 180.0f : 0);
                                                                             
  _verTrLeft.rotation = Quaternion.Euler(0, 0, _verTrLeft.localPosition.y < 0 ? 180.0f : 0);

}
6. projects with my participation

Harvester simulator on Unity, sets of psychophysiological tests

7. Education

Radio Engineering Faculty, Volga State University, Russia, master's degree

8. english language level

B1 level
