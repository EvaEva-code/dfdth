using System.Collections;
using System.Collections.Generic;
using UnityEngine;

public class ScenceChange : MonoBehaviour
{


    public string sceneName;

    void OnTriggerEnter()



       EditorSceneManager LoadScene(sceneName)
}


using System.Collections;
using System.Collections.Generic;
using UnityEngine;

public class Trampoline : MonoBehaviour
{
    void OnTriggerEnter(Collider other)

    { other.GetComponent<Jump>().JumpStrength = 10


             }
    void OnTriggerExit(Collider other)

    { other.GetComponent<Jump>().JumpStrength = 2
            
            
            
            }

