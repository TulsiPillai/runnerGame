using UnityEngine;
using System.Collections;

public class playSound : MonoBehaviour {

	private AudioSource[] _audiSource;
	// Use this for initialization
	void Start () {
		_audiSource = this.GetComponents<AudioSource> ();
	}
	
	// Update is called once per frame
	void Update () {

	}

	public void PlaySound(string type){

		switch (type) {

		case "jump":
			_audiSource[0].Play();
			break;
		case "powerup":
			_audiSource[1].Play();
			break;
		case "die":
			_audiSource[2].Play();
			break;
		case "restart":
			_audiSource[3].Play();
			break;
		}

		
	}

	




}
